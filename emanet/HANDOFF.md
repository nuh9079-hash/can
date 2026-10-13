# Emanet — Project Handoff

## Current known demo
- Demo URL: https://emanet-kayip-esya-demo.cab541122.chatgpt.site/
- This is a saved reference to the demo, not proof that source code is deployed to Supabase or Vercel.

## Project purpose
A lost-and-found reporting demo intended for a Nilüfer Belediyesi presentation. Keep the concept civic-service focused; do not make AI the main selling point.

## Main flows
- `/kayip-bildir`: owner reports a lost item with details such as where/when it was lost, color and other identifying details.
- `/buluntu-bildir`: finder submits an item photo and handoff/location details.
- Matching reports should lead to a notification to the likely owner.
- e-Devlet integration should be shown as a future feature with a disabled note: “e-Devlet entegrasyonu yakında aktif olacak.”
- `/personel`: demo staff view; direct URL access should redirect home with “Lütfen ana menüden devam edin.”
- Staff mock data requested: 3 pending (yellow), 2 completed (green), 1 expired (red).
- KVKK contact shown in footer: kvkk@emanet.tr
- Mobile layout target: 375px.
- Improve “Ekibe katılma / Sizinle çalışma” wording/section.

## Project ownership / pitch
Present as the user's own initiative (Nuh / Ercan name fields as previously requested), with the municipality as the intended audience.

## Storage and deployment status (checked 2026-10-13)
- Supabase connected account lists a project named “Nova Blok” only; no project named Emanet was found.
- Vercel project search for “emanet” returned no projects.
- GitHub connected account lists repositories `nuh9079-hash/can` (private, empty) and `nuh9079-hash/brandflow-ai`; no Emanet repository was listed.
- Therefore this file preserves the project brief and demo link only. The original app source files have NOT been added to GitHub by this action, and no Supabase/Vercel deployment has been created.

## Next step
Locate/export the actual Emanet source project, then create a dedicated GitHub repository and deploy to Vercel. Connect Supabase only if the app needs a real database/authentication. Verify the app flows and environment variables before calling it production-ready.
