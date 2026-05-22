# Website QA Prompt

Paste the text below into a fresh chat. Attach all four HTML files (or open the folder) when you use it.

---

I have a four-page marketing website I need you to QA before it goes live. The pages are:

- index.html (Home)
- check-up.html (The First Look — free intro offer)
- mot.html (The Marketing MOT — £495 offer)
- built-to-be-booked.html (Built to Be Booked — done-for-you offer)

They're standalone HTML files with inline CSS. Please read all four, then give me a single structured report covering the sections below. Don't change any files — just tell me what you find, with the specific file and line where relevant.

ABOUT THE BUSINESS (so you can judge tone and personality):
Stellar Marketing Studio — I'm Sarah, a marketing freelancer who helps women business owners (dog trainers, therapists, coaches, accountants, consultants etc.) become "the one their ideal clients can't ignore." My whole pitch is personality-led: people buy the person, not just the service. My voice is warm, chatty, British, plain English, short sentences, active voice. Signature phrases: "marketing fairy godmother", "gold dust", "I have to work with her", "brain fog", "just sits there". I never use marketing jargon (unlock, leverage, elevate, journey, empower, authentic) and never use em dashes.

1. VISUAL CONSISTENCY ACROSS PAGES
- Fonts: every page should use Fraunces (headings) and Nunito Sans (body). Flag any mismatch in font family, weight or sizing scale between equivalent elements.
- Colours: check the CSS colour variables match across all four files (navy, cream/paper, stone, etc.). Flag any page using a different hex or naming.
- CTA buttons: the pill/button styles should look and behave the same across pages — same padding, letter-spacing, hover behaviour, filled vs outline variants. Flag inconsistencies.
- Section rhythm: backgrounds should alternate sensibly (no two identical-coloured sections butting together with an invisible divider).
- Nav and footer: should be consistent across all four pages — same links, same names, same styling, same star colour.

2. LINKS AND NAVIGATION
- Check every internal link (index.html, check-up.html, mot.html, built-to-be-booked.html) points to a real page and the right one.
- Check anchor links like #contact actually have a matching id on that page.
- Flag any dead, wrong, or placeholder links.

3. FORMS AND INTERACTIVE ELEMENTS
- Check the WhatsApp and email (mailto) buttons are wired up correctly and the JS has no errors.
- Check the FAQ accordions and any sliders/toggles have working JavaScript.
- Flag anything referencing an element ID that doesn't exist.

4. READABILITY AND COPY
- Read each page start to finish as a real visitor would. Does it flow? Any clunky sentences, repetition, or places where the same point is made too many times?
- Flag anything confusing, and anywhere a section feels too text-heavy.

5. PERSONALITY / BRAND VOICE
- Point out where the copy sounds generic or could be more "me" (warm, chatty, personality-led).
- Flag any banned jargon or em dashes.
- Tell me where my personality is missing and could come through more strongly.

6. FINAL MANUAL CHECKLIST FOR ME
- Give me a short checklist of things I need to test myself in a browser before launch (e.g. click every button, submit the forms, test on mobile, check images load, etc.).

Format the report by page where it makes sense, and by theme where it doesn't. Be specific and practical. Prioritise anything that would actually break or confuse a visitor.
