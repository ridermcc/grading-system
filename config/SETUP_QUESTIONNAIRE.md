# Professor Setup Questionnaire

> **Instructions for Claude**: Ask these questions ONE AT A TIME in a conversational flow.
> Do NOT dump all questions at once. Wait for each answer before moving on.
> If an answer is vague, push back and ask for specifics.
> After all questions are answered, generate `professor_preferences.md` and the three rubrics.

---

## SECTION 1: Course Context

### 1.1 — Course Information
- What course is this for? (course name, number, level — undergrad/grad?)
- How many students are in the class?
- What is the primary learning objective of this assignment?

### 1.2 — Assignment Context
- What scenario or prompt did you give students for these three documents?
  - Are they applying to a specific type of job/industry?
  - Is there a fictional company or real one?
  - Did you provide a job description they're responding to?
- Are the resume, cover letter, and email all related to the same scenario, or independent assignments?

### 1.3 — Student Level Expectations
- What year are most students? (freshman, sophomore, junior, senior, grad?)
- Should I grade to professional-world standards, or adjusted for their academic level?
- Have students received instruction on these document types before this assignment?

---

## SECTION 2: Grading Scale & Weight

### 2.1 — Scoring System
- What scoring system do you use?
  - Letter grades (A/B/C/D/F)?
  - Points out of 100?
  - Points out of a custom total?
  - Rubric-based categories (Exceeds/Meets/Approaching/Below)?
- What is the total point value for this assignment?
- How are points distributed across the three documents?
  - Resume: _____ points/percentage
  - Cover Letter: _____ points/percentage
  - Email: _____ points/percentage
  - Are they weighted equally or differently? Why?

### 2.2 — Grade Thresholds
- What score range constitutes an A? B? C? etc.
- Is there a minimum passing score?
- Do you use plus/minus grades (A-, B+, etc.)?

---

## SECTION 3: Resume Rubric Deep-Dive

### 3.1 — Format & Structure
- Do you require a specific format? (chronological, functional, combination?)
- Is there a required length? (one page only? two pages acceptable?)
- Do you have formatting requirements? (font, margins, file type?)
- Should students include an objective/summary statement, or do you consider that outdated?
- What sections MUST be present? (education, experience, skills, etc.)
- Are there sections you explicitly do NOT want? (references, photo, personal info?)

### 3.2 — Content Quality
- How do you evaluate bullet points under experience?
  - Do you require action verbs?
  - Do you require quantified results/metrics?
  - How important is specificity vs. brevity?
- How do you evaluate the skills section?
  - Do you want hard skills, soft skills, or both?
  - Should skills be tailored to the job description?
- How important is tailoring the resume to the specific job/scenario vs. a general resume?

### 3.3 — Common Mistakes You Care About
- What are the top 3-5 mistakes that will cost students the most points on a resume?
- Are there any instant deal-breakers (automatic significant deduction)?
- How harshly do you grade typos/grammatical errors?

---

## SECTION 4: Cover Letter Rubric Deep-Dive

### 4.1 — Format & Structure
- Do you require a specific cover letter format? (block style, modified block?)
- Required length? (one page? specific word count?)
- Must it follow formal business letter formatting? (date, address block, salutation, etc.)
- How many paragraphs do you expect?

### 4.2 — Content Expectations
- What should the opening paragraph accomplish?
- What should the body paragraphs cover?
  - Connection to the company/role?
  - Specific examples from experience?
  - How they'd add value?
- What should the closing paragraph include?
- How important is demonstrating knowledge of the company/role?
- Should they reference their resume?

### 4.3 — Tone & Voice
- What tone are you looking for? (formal, professional but warm, confident but not arrogant?)
- How do you feel about first-person perspective?
- Should students avoid certain phrases? (e.g., "I believe I would be a great fit")
- Any phrases or approaches you specifically like to see?

### 4.4 — Common Mistakes You Care About
- Top 3-5 cover letter mistakes that cost the most points?
- Any instant deal-breakers?
- How do you feel about generic/template cover letters that aren't tailored?

---

## SECTION 5: Professional Email Rubric Deep-Dive

### 5.1 — Email Scenario
- What is the email scenario? (following up on an application, networking, requesting information, thank you after interview, etc.)
- Who is the recipient? (hiring manager, professor, professional contact?)
- What is the expected formality level?

### 5.2 — Format & Structure
- Do you require a specific subject line format?
- Expected length? (word count or paragraph count?)
- Required components? (greeting, purpose, call to action, professional closing, signature block?)
- What should the email signature include?

### 5.3 — Content & Tone
- What's the #1 thing this email needs to accomplish?
- How do you evaluate professionalism vs. personality?
- How important is conciseness?
- Should students reference specific details (from a meeting, job posting, etc.)?

### 5.4 — Common Mistakes You Care About
- Top 3-5 email mistakes?
- How harshly do you grade email etiquette issues? (Reply-all mistakes, poor subject lines, etc.)
- Are there any email conventions you feel strongly about?

---

## SECTION 6: Overall Grading Philosophy

### 6.1 — Feedback Preferences
- How detailed should feedback be? (brief notes, paragraph explanations, inline annotations?)
- Do you want feedback written as if the student will read it, or just for your reference?
- Should I highlight strengths as well as weaknesses?
- Do you want a "top priority improvement" for each student?

### 6.2 — Consistency & Edge Cases
- How should I handle borderline cases? (e.g., between a B+ and A-)
- If a student's content is excellent but formatting is poor, how does that weigh?
- If a student clearly used AI to write their materials, should I flag that? How should it affect the grade?
- How do you handle late submissions? (is that my concern or yours?)
- What if a student submits the wrong file or an incomplete submission?

### 6.3 — Your Pet Peeves
- What are your personal grading pet peeves that aren't on any rubric but influence your grading?
- Is there anything you're particularly generous about?
- Any specific industry conventions or standards you insist on?

### 6.4 — Final Calibration
- Can you share an example of A-level work and C-level work for any of the three documents?
- If you had to rank the three documents by what you care about most, what's the order?
- Is there anything else that affects your grading that I haven't asked about?

---

## POST-QUESTIONNAIRE: Claude's Next Steps

After all questions are answered:

1. ✅ Compile answers into `config/professor_preferences.md`
2. ✅ Generate `rubrics/resume_rubric.md` with specific point breakdowns
3. ✅ Generate `rubrics/cover_letter_rubric.md` with specific point breakdowns
4. ✅ Generate `rubrics/email_rubric.md` with specific point breakdowns
5. ✅ Present the complete rubrics to the professor for approval
6. ✅ Make any adjustments the professor requests
7. ✅ Confirm the system is ready for grading

**The professor must explicitly approve all three rubrics before any grading begins.**
