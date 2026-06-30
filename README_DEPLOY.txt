MiraCell company portal update
==============================

Files included:
- index.html: updated MiraCell Internal System portal with a fourth protected icon named "IDIEX Material QC".
- quality-test/index.html: the uploaded Quality_test project placed under /quality-test/ and protected from direct access.

New icon password:
4444

Deployment:
1. Open the GitHub repository connected to https://miracell-company.vercel.app/.
2. Replace the existing root index.html with the included index.html.
3. Upload the full quality-test folder to the repository root.
4. Commit and push. Vercel will redeploy automatically.
5. Open https://miracell-company.vercel.app/ and click IDIEX Material QC.

Notes:
- The existing three cards keep their current hashed passwords and URLs.
- The new Quality project is also protected if opened directly at /quality-test/.
- This is client-side password protection, matching the existing portal style. For strong security, use server-side authentication later.
