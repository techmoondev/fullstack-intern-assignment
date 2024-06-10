# TMD: FullStack Intern Assignment

## Overview

This assignment involves setting up a simple username/password authentication system using Redux for state management and Next.js for the front-end and back-end. You will create API endpoints with bearer token authentication and implement a custom `useAuthSession` hook to manage the user's session on the client side.

## Your Tasks

1. **Implement the `useAuthSession` Hook**:

   - In `hooks/useAuthSession.ts`, create a custom hook that manages the user's authentication session.
   - The hook should handle checking if a user is authenticated and fetching user data.

2. **Create and Complete the API Endpoints**:

   - create the required apis

3. **Bearer Token Authentication**:
   - Implement bearer token authentication in your API endpoints.
   - Ensure that API requests are secured and only accessible to authenticated users.

## Example Usage of useAuthSession Hook

```bash
const { user } = useAuthSession();

if (user) {
  console.log('User:', user.username);
}
```

## Estimated Time

Please spend no more than 3-4 hours on this assignment and submit whatever you can complete within that time frame.

## Bonus Tasks

1. Add validation checks for the login form.
2. Show toast notifications for errors and successful login.

## Submission

1. Ensure all your changes are committed.
2. Push your changes to a new repository on your personal GitHub account with public access.
3. Provide a link to your repository, along with your email and phone number, in the provided Google Form. Do not create pull requests in the shared repository.
