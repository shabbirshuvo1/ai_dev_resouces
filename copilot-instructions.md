# Copilot Instructions

## App: TaskFlow Pro
Task management application for teams with project tracking, time tracking, and analytics.

## Tech Stack

### Frontend
- React 18 + TypeScript
- Redux Toolkit
- Tailwind CSS
- React Router v6
- Vite

### Backend
- Node.js + Express + TypeScript
- PostgreSQL + Prisma ORM
- JWT auth
- REST API

### DevOps
- Docker + GitHub Actions
- AWS (ECS, RDS, S3)

## Best Practices

### Code Quality
- Use strict TypeScript
- Follow ESLint + Prettier config
- Component-based architecture
- Feature-based organization
- SOLID principles

### React
- Functional components with hooks
- Extract reusable logic to custom hooks
- Memoize expensive operations
- Lazy-load components and routes

### State Management
- Use Redux Toolkit slices
- Normalize state structure
- Employ selectors for data access
- Handle async with createAsyncThunk

### Styling
- Use Tailwind utility classes directly
- Create component abstractions for repetitive patterns
- Mobile-first responsive design

### API
- RESTful endpoints with proper status codes
- Input validation on all endpoints
- Consistent error responses
- Resource-based URL structure

### Database
- Use Prisma migrations
- Implement proper indexes
- Use transactions for related operations
- Soft delete where appropriate

### Security
- Sanitize all user inputs
- Store secrets in environment variables
- Hash passwords with bcrypt
- Use HTTPS only
- Set secure and HTTP-only cookies

### Testing
- Jest + React Testing Library
- Unit test hooks and utilities
- Integration test components and API
- Use factories for test data

### Performance
- Code splitting for routes
- Optimize image assets
- Use pagination for large datasets
- Index database queries

### Accessibility
- Semantic HTML
- Keyboard navigation
- ARIA attributes where needed
- Sufficient color contrast

## Project Structure
Keep frontend organized by features:
```
src/
├── components/
├── features/
├── hooks/
├── services/
├── store/
└── utils/
```

Keep backend organized by responsibility:
```
src/
├── controllers/
├── middlewares/
├── routes/
├── services/
└── utils/
```

## Git Workflow
- Feature branches
- Conventional commits
- Pull requests with reviews
- CI/CD via GitHub Actions
