# Google Docs Clone

![Google Docs Clone Banner]()

This is a Google Docs clone built with **Next.js 15**, **React**, **Tailwind CSS**, and real-time collaboration features using **Liveblocks**, **Convex**, and **Clerk** for authentication.

⭐ **Please give a star to my repo; it will help me a lot!** ⭐

---

## Features

- **Real-time collaboration**
- **Rich text editing** with support for:
  - Tables
  - Images with resizing
  - Task lists
  - and many more...
- **Customizable themes** with Tailwind CSS
- **Responsive design**
- **Toolbar for common actions**

---

## Getting Started

### Prerequisites

Before you begin, ensure you have the following:

- **Node.js** installed on your machine
- An account on [Convex](https://convex.dev)
- An account on [Clerk](https://clerk.dev)
- An account on [Liveblocks](https://liveblocks.io)

### Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/sufiprog/docs-clone.git
   cd docs-clone
   npm install
   ```

2. **Set up Convex:**
   - Create an account on Convex and create a new project.
   - Follow the instructions to set up your database.
   - Copy the Convex deployment URL and secret code.

3. **Set up Clerk:**
   - Create an account on Clerk and create a new application.
   - Copy the Clerk publishable key and secret key.

4. **Set up Liveblocks:**
   - Create an account on Liveblocks and create a new project.
   - Copy the Liveblocks public key and secret key.

5. **Create a `.env.local` file:**
   - Add the following environment variables to the file in the root directory of your project:

     ```env
     CONVEX_DEPLOYMENT=your_convex_secret_code
     NEXT_PUBLIC_CONVEX_URL=your_convex_public_url

     NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
     CLERK_SECRET_KEY=your_clerk_secret_key

     LIVE_BLOCK_SECRET_KEY=your_liveblocks_secret_key
     ```

6. **Run the development server:**

   ```bash
   npm run dev
   ```

   Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

---

## Deployment

The easiest way to deploy your Next.js app is to use the **Vercel Platform**, created by the Next.js team.

### Deploy on Vercel:

1. Sign up for a [Vercel](https://vercel.com) account if you don’t have one.
2. Import your project from GitHub.
3. Add the same environment variables in the Vercel dashboard.
4. Deploy your project.

---

## Learn More

To learn more about the technologies used in this project, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - Learn about Next.js features and API.
- [Convex Documentation](https://docs.convex.dev) - Learn about Convex features and API.
- [Clerk Documentation](https://clerk.dev/docs) - Learn about Clerk features and API.
- [Liveblocks Documentation](https://liveblocks.io/docs) - Learn about Liveblocks features and API.

---

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

---

## License

This project is licensed under the **MIT License**.

