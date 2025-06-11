# Ministry to the Sick Portal

This is the official web portal for the Ministry to the Sick at Queen of Peace Catholic Church.

## 🚀 Deployment (GitHub Pages)

1. Push all files to a new GitHub repository.
2. In repo settings, enable GitHub Pages under `Pages`.
3. Set the branch to `main` and folder to `/ (root)`.
4. Your site will be live at `https://your-username.github.io/your-repo-name/`.

## 📬 Google Form

The form is embedded in `index.html`. To change it:
- Open the shared Google Form
- Click `Send > Embed` and replace the `iframe` src in `index.html`

## 📧 Zapier Email Setup

1. Go to [Zapier.com](https://zapier.com).
2. Trigger: **New Form Response in Google Forms**
3. Action: **Send Email in Gmail** (or use MailerSend/SMTP)
4. Use response fields to customize:
   - Coordinator: `purtillg@comcast.net`
   - Submitter: Form's email address field

## ✅ Customize Further

- `css/styles.css`: Styles
- `js/portal.js`: JS for modals and animations
