# oRPC Boost TS and TanStackQuery

This project designed to explore and implement oRPC (Optimized Remote Procedure Call) functionality. The project includes a basic setup for a server-side rendered application with TypeScript support and Prisma integration for database management.

## Getting Started

### Prerequisites

- Node.js (version 18 or higher recommended)
- npm, yarn, pnpm, or bun (package manager of your choice)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sxidsvit/learn-orpc.git
   cd learn-orpc
   ```
2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```
3. Set up the Prisma database (if not already configured):
   ```bash
   npx prisma db push
   npx prisma generate
   ```

### Running the Development Server

Start the development server with one of the following commands:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

### Editing the Project

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

## Features

- **Next.js**: Utilizes the latest features of Next.js for server-side rendering and static site generation.
- **TypeScript**: Type-safe development with full TypeScript support.
- **Prisma**: Integrated database ORM for managing data with a generated client in `./generated/prisma`.
- **ORPC**: Implements a custom ORPC server for optimized remote procedure calls (see `lib/orpc.server.ts`).
- **Geist Font**: Uses `next/font` to optimize and load the Geist font family.

## Learn More

To learn more about the technologies used in this project, check out the following resources:

- [Next.js Documentation](https://nextjs.org/docs)
- [oRPC Documentation](https://orpc.unnoq.com/docs/getting-started)
- [Prisma Documentation](https://www.prisma.io/docs)
- [GitHub Repository](https://github.com/sxidsvit/learn-orpc) - Feel free to contribute!

## Deploy on Vercel

The easiest way to deploy this Next.js app is to use the [Vercel Platform](https://vercel.com/) from the creators of Next.js. Check out the [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
<<<<<<< HEAD

## Project Structure

- `lib/`: Contains utility files like `db.ts` for Prisma setup and `orpc.server.ts` for ORPC logic.
- `app/`: Main application files, including `page.tsx` for the homepage.
- `prisma/`: Schema and configuration for Prisma.
- `generated/prisma/`: Auto-generated Prisma Client files.

### Contact

Connect with the project maintainer:

[<img alt="Sergiy Antonyuk | LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" />][linkedin]

[linkedin]: https://www.linkedin.com/in/sergiy-antonyuk/

#### 🙏 Acknowledgements

# Special thanks to [Jan Marshal](https://www.youtube.com/@janmarshalcoding) for his invaluable contributions.

## Project Structure

- `lib/`: Contains utility files like `db.ts` for Prisma setup and `orpc.server.ts` for ORPC logic.
- `app/`: Main application files, including `page.tsx` for the homepage.
- `prisma/`: Schema and configuration for Prisma.
- `generated/prisma/`: Auto-generated Prisma Client files.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by the Vercel and Prisma communities.
- Thanks to the open-source contributors of Next.js and related libraries.
  > > > > > > > 6194f398b47dd3a8ae726208302723e98b4f6c1c
