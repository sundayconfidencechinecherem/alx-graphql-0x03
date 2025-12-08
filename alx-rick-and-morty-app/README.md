
# Rick and Morty GraphQL Application

A Next.js application for browsing Rick and Morty episodes using GraphQL with Apollo Client.

## Project Setup

### Technologies Used
- **Next.js 14** (Pages Router)
- **TypeScript** for type safety
- **Tailwind CSS** for styling
- **Apollo Client** for GraphQL integration
- **GraphQL** query language

### Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run development server:
   ```bash
   npm run dev
   ```

### Dependencies
- `@apollo/client`: Apollo Client for React
- `graphql`: GraphQL implementation
- `@types/graphql`: TypeScript definitions for GraphQL

### Project Structure
```
alx-rick-and-morty-app/
├── graphql/
│   ├── apolloClient.ts    # Apollo Client configuration
│   └── queries.ts         # GraphQL query definitions
├── pages/
│   └── _app.tsx           # Next.js App with Apollo Provider
├── public/
├── styles/
│   └── globals.css        # Global styles
└── package.json
```

### GraphQL Configuration
- **API Endpoint:** `https://rickandmortyapi.com/graphql`
- **Client:** Apollo Client with InMemoryCache
- **Query:** GET_EPISODES for paginated episode data

### Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm start` - Start production server
- `npm run lint` - Run ESLint

### Development
The application is configured with:
- TypeScript for type safety
- Tailwind CSS for utility-first styling
- ESLint for code quality
- Apollo Client for GraphQL state management

### Next Steps
- Implement episode browsing UI
- Add pagination controls
- Implement search and filtering
- Add character information display
```

### **Step 10: Test Your Setup**

```bash
# Start the development server
npm run dev
```

**Open your browser and go to:** `http://localhost:3000`

You should see the default Next.js page. Check the browser console for any errors.

### **Step 11: Verify Everything is Working**

**Check these in your browser console (F12):**
1. No Apollo Client connection errors
2. No TypeScript compilation errors
3. Application loads successfully

## ✅ **What You Should Have Now**

### **File Structure:**
```
alx-graphql-0x01/
└── alx-rick-and-morty-app/
    ├── graphql/
    │   ├── apolloClient.ts
    │   └── queries.ts
    ├── pages/
    │   └── _app.tsx
    ├── README.md
    ├── package.json
    ├── tsconfig.json
    ├── tailwind.config.ts
    └── next.config.js
```

### **Key Files Created/Modified:**
1. ✅ `graphql/apolloClient.ts` - Apollo Client configuration
2. ✅ `graphql/queries.ts` - GraphQL query definitions  
3. ✅ `pages/_app.tsx` - Next.js App with Apollo Provider
4. ✅ `README.md` - Project documentation
5. ✅ `package.json` - Dependencies installed
