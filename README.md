# Full Stack AI Finance Platform

A full-stack AI-powered finance platform built with **Next.js**, **Supabase**, **Prisma**, **Clerk**, **Tailwind CSS**, **Shadcn UI**, **Inngest**, **ArcJet**, **Resend**, and **Gemini AI**.  

---

## ✨ Features

- 🔑 Authentication with **Clerk**
- 🤖 AI-powered financial insights via **Gemini AI**
- 🗄️ Supabase + Prisma for database and ORM
- 🎨 Clean UI with **Tailwind CSS** and **Shadcn UI**
- ⚡ Background job processing with **Inngest**
- 🛡️ Security via **ArcJet**
- 📧 Email notifications with **Resend**
- 📊 Real-time dashboard and analytics

---

## 🛠 Tech Stack

| Layer        | Tools / Technologies |
|--------------|----------------------|
| Framework    | Next.js |
| UI           | Tailwind CSS + Shadcn UI |
| Auth         | Clerk |
| Database     | Supabase (PostgreSQL) + Prisma |
| Background   | Inngest |
| Security     | ArcJet |
| AI           | Gemini AI (via GEMINI_API_KEY) |
| Email        | Resend |
| Hosting      | Vercel (or any platform) |

---

## ⚙️ Environment Variables
DATABASE_URL=
DIRECT_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding
GEMINI_API_KEY=
RESEND_API_KEY=
ARCJET_KEY=


Replace each with your actual credentials.

---

## 🚀 Getting Started

1. **Clone the repo**
   ```bash
   git clone <your-repo-url>
   cd <project-folder>
2. Install dependencies
npm install

3. Run development server
npm run dev


📌 Usage

- Sign in / Sign up using Clerk authentication.

- Dashboard provides AI-driven insights and visual reports.

- Add transactions (income/expenses) with real-time updates.

- Background workflows (like report generation) run on Inngest.

- ArcJet secures forms and APIs.

- Resend sends confirmation emails and alerts.


🤝 Contribution

Contributions and suggestions are welcome. Please open an issue or submit a pull request.
