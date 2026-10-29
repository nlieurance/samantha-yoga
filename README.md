# Samantha Lieurance — Yoga & Meditation

A static, responsive website for group classes, private lessons, studio and fitness-center partnerships, and corporate, nonprofit, and community events.

## Connect the Formspree form

1. Create a form in Formspree and copy its endpoint. It looks like `https://formspree.io/f/xxxxxxxx`.
2. Open `index.html` and find `FORM_ID_HERE` in the form's `action` attribute.
3. Replace `FORM_ID_HERE` with the ID from your Formspree endpoint. For example, `https://formspree.io/f/xxxxxxxx`.
4. In Formspree, confirm the notification address and submit a test inquiry after deployment.

The form asks for a name, email, organization, inquiry type, possible date or timeframe, location, and a short message. It includes a basic honeypot field. Do not ask visitors to submit sensitive health information through this form.

## Deploy to Vercel

This is a static site and has no build step or package dependencies.

- Put `index.html` at the project root of a Git repository and import that repository in Vercel.
- Choose **Other** as the framework preset. Leave the build command blank and use `.` as the output directory if Vercel requests one.
- Alternatively, install the Vercel CLI and run `vercel` from this folder.

The photos and web fonts load from Unsplash and Google Fonts. Replace them with licensed or owned assets if you prefer to keep all assets within your project.

The hero currently uses a temporary yoga stock photo. LinkedIn requires sign-in to view Sam's profile photo, so that image could not be retrieved from the public profile. When you have Sam's photo, replace the hero image URL in `index.html` with the photo's hosted URL or a local asset path.
