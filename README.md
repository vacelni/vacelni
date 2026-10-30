### Hi, I'm Vacel 👋

I build software that small businesses run on every day, and computer-vision tools for industry. Computer engineering graduate (2026) based in Semarang, Indonesia (UTC+7), currently a vision R&D intern, and **open to remote engineering roles**.

**Portfolio:** [vacelni.vercel.app](https://vacelni.vercel.app) · **Email:** vacelfaizfadeli28@gmail.com · **LinkedIn:** [vacelnino-faiz-fadeli](https://linkedin.com/in/vacelnino-faiz-fadeli)

#### In production

- **[WarungKasir](https://github.com/vacelni/warung-kasir)**: an offline-first point-of-sale PWA that a food stall uses every day. Sales are saved on the phone first and synced exactly once. Receipts print over Web Bluetooth, and Postgres row-level security keeps each role's data separate. Tested with 1,094 unit tests, 365 pgTAP assertions and Playwright. [Try the demo](https://warungkasir-demo.pages.dev).
- **[P3L training platform](https://github.com/vacelni/p3l-showcase)**: class registration, automatic e-invoicing and an admin dashboard for a wastewater consulting firm, with rate limiting that holds up on serverless. [Live site](https://pengolahanlimbahcair.com).

#### Other projects

- **[Relasi CRM](https://github.com/vacelni/relasi-crm)** is a multi-tenant CRM for small sales teams: contacts, a deal pipeline, tasks and a WhatsApp-first activity log, with owner and sales roles enforced by Postgres row-level security. It scores leads and drafts follow-ups (rule-based when no AI key is set) and takes upgrades through Midtrans, with webhook signatures and amounts checked server side. Tested with Vitest, pgTAP and Playwright. [Try the demo](https://relasicrm.vercel.app).
- **[MachineWatch](https://github.com/vacelni/machinewatch)** predicts remaining useful life for a fleet of jet engines from streaming sensor data (NASA C-MAPSS, test RMSE 14.5 cycles) and shows it on a live dashboard. Uses FastAPI with server-sent events, a model registry with a promotion gate, and Docker Compose.
- **[Indonesian short-answer scoring](https://github.com/vacelni/indo-short-answer-scoring)** scores students' answers 0–5 against the teacher's key and shows its evidence. I evaluated it on questions the model has never seen (QWK 0.57), after finding and fixing data leakage in my first version. Uses scikit-learn, multilingual embeddings, an IndoBERT cross-encoder and FastAPI.
- **[Smart Kebaya pattern drafting](https://github.com/vacelni/smart-kebaya-pattern)** drafts a made-to-measure kebaya pattern from 15 measurements and draws it to scale. Built with Kotlin Compose Multiplatform for Android and the web (Wasm).

#### Research

- **PPE detection on low-resource hardware**: undergraduate thesis comparing YOLOv5-Nano and YOLOv8-Nano on 2,512 images, tested for significance with the Wilcoxon signed-rank test.

#### Tools I use

TypeScript, React, Next.js, Node.js, PostgreSQL, Supabase, Tailwind CSS · Python, PyTorch, scikit-learn, Ultralytics YOLO, OpenCV, FastAPI · Kotlin, Jetpack Compose · Git, GitHub Actions, Docker, Vercel, Cloudflare
