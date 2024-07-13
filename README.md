[![Fullstack Notion Clone](https://github.com/soumojit622/next13-notion-clone/blob/master/public/banner.png)](https://taskflow-blue.vercel.app/)
# 📝 Notion Clone Website

This is a Notion clone website built with [Next.js 13](https://nextjs.org/), [React](https://reactjs.org/), [Convex](https://convex.dev/), [Tailwind CSS](https://tailwindcss.com/), [Prisma](https://www.prisma.io/), [Clerk](https://clerk.dev/) authentication, and [Shadcn UI](https://shadcn.dev/). The project aims to replicate the core functionalities of Notion while providing additional features and a customizable UI.

## 🚀 Key Features

- **Real-time Database**: 🔗 Real-time data synchronization powered by [Convex](https://convex.dev/).
- **Notion-Style Editor**: 📝 Intuitive editor inspired by [Notion](https://www.notion.so/).
- **Light and Dark Mode**: 🌓 Switch between light and dark themes seamlessly.
- **Infinite Children Documents**: 🌲 Create and manage nested documents with ease.
- **Trash Can & Soft Delete**: 🗑️ Recover deleted documents from the trash.
- **Authentication**: 🔐 Secure user authentication via [Clerk](https://clerk.dev/).
- **File Operations**: 📁 Manage files and attachments within your notes.
- **Icons for Each Document (Changes in Real-Time)**: 🌠 Personalize your documents with unique icons.
- **Expandable Sidebar**: ➡️🔀⬅️ Easily navigate through documents with an expandable sidebar.
- **Full Mobile Responsiveness**: 📱 Optimized for mobile and tablet devices.
- **Publish Your Note to the Web**: 🌐 Share your notes online with a public URL.
- **Fully Collapsible Sidebar**: ↕️ Collapse the sidebar for a distraction-free workspace.
- **Landing Page**: 🛬 Attractive landing page to welcome users.
- **Cover Image for Each Document**: 🖼️ Add cover images to make your documents stand out.
- **Recover Deleted Files**: 🔄📄 Retrieve deleted files effortlessly.

## 🌐 Demo

Check out the live demo: [Notion Clone Demo](https://taskflow-blue.vercel.app/)

## 🛠️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/soumojit622/next13-notion-clone.git
    cd notion-clone
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env.local` file in the root of the project.
    - Add your environment variables (e.g., database URL, API keys, etc.) to this file.

    Example:
    ```env
    CONVEX_DEPLOYMENT=
    NEXT_PUBLIC_CONVEX_URL=

    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
    CLERK_SECRET_KEY=

    EDGE_STORE_ACCESS_KEY=
    EDGE_STORE_SECRET_KEY=
    ```


4. Run the development server:
    ```bash
    npm run dev
    ```

    Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## 🛠️ Technologies Used

- **Next.js 13**: Framework for building server-side rendered React applications. [Learn more](https://nextjs.org/)
- **React**: JavaScript library for building user interfaces. [Learn more](https://reactjs.org/)
- **Convex**: Real-time database and backend framework. [Learn more](https://convex.dev/)
- **Tailwind CSS**: Utility-first CSS framework. [Learn more](https://tailwindcss.com/)
- **Prisma**: Database ORM for Node.js and TypeScript. [Learn more](https://www.prisma.io/)
- **Clerk**: Authentication and user management solution. [Learn more](https://clerk.dev/)
- **Shadcn UI**: UI component library. [Learn more](https://shadcn.dev/)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Push your branch to your fork.
5. Open a Pull Request.

For major changes, please open an issue first to discuss what you would like to change.

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## 🙏 Acknowledgements

- Thanks to the creators of the open-source libraries and tools used in this project.
- Special thanks to [Notion](https://www.notion.so/) for the inspiration.

---

Feel free to reach out if you have any questions or need further assistance.

Happy coding! 🚀

## 🔮 Future Plans

- **Collaboration Features**: Real-time collaboration with multiple users.
- **Advanced Permissions**: Granular permissions for sharing and editing documents.
- **Customizable Themes**: Allow users to create and apply custom themes.
- **API Integration**: Integrate with external APIs for enhanced functionality.

Stay tuned for more updates!
