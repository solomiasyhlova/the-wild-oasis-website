# The Wild Oasis 🌲

A modern hotel booking web application for a boutique collection of luxury cabins. Guests can browse cabins, check real-time availability, make reservations, and manage their bookings through a clean, fully responsive interface.

**Live demo:** [the-wild-oasis-website-demo-two-steel.vercel.app](https://the-wild-oasis-website-demo-two-steel.vercel.app/)

---

## ✨ Features

- **Browse cabins** with detailed descriptions, capacity, pricing, and image galleries
- **Filter cabins** by guest capacity (2–3, 4–7, 8–12 guests)
- **Real-time availability** and date-range selection for reservations
- **Authentication** via Google Sign-In (NextAuth)
- **Reservation management** — create, view, update, and cancel your bookings
- **Guest profile** — update personal details used at check-in
- **Server-side rendering & dynamic routing** with the Next.js App Router
- **Fully responsive** layout for desktop, tablet, and mobile

---

## 📸 Screenshots

### Home
![Home page](.github/screenshots/home.png)

### Cabins
![Cabins listing](.github/screenshots/cabins.png)

### About
![About page](.github/screenshots/about.png)

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Framework | [Next.js 14](https://nextjs.org/) (App Router, Server Components, SSR) |
| UI | [React 18](https://react.dev/), [Tailwind CSS](https://tailwindcss.com/) |
| Auth | [NextAuth.js v5](https://authjs.dev/) (Google provider) |
| Database & Backend | [Supabase](https://supabase.com/) |
| Dates | [react-day-picker](https://daypicker.dev/) + [date-fns](https://date-fns.org/) |
| Icons | [Heroicons](https://heroicons.com/) |
| Deployment | [Vercel](https://vercel.com/) |

---

## 📁 Project Structure

```
the-wild-oasis-website/
├── app/              # Routes, layouts, server components & data services
├── public/           # Static assets (images, icons, screenshots)
├── middleware.js     # Route protection / auth middleware
├── next.config.mjs   # Next.js configuration
└── tailwind.config.js
```

---

## 🌐 Deployment

The app is deployed on **Vercel**. Push to the `main` branch (or connect the repo in the Vercel dashboard) and add the environment variables above in your project settings to deploy.

---

## 📄 License

This project was built for learning and portfolio purposes.
