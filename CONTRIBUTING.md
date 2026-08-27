# Contributing to Donor Assistance App

Thank you for your interest in contributing! We welcome contributions from developers, designers, and others who want to help make a difference.

## How to Contribute

### Reporting Bugs
1. Check if the bug has already been reported in [Issues](https://github.com/sonaws14331/donor-assistance-app/issues)
2. If not, create a new issue with:
   - Clear title describing the bug
   - Detailed description of the problem
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Screenshots (if applicable)
   - Your environment (OS, Node version, etc.)

### Suggesting Features
1. Check [Issues](https://github.com/sonaws14331/donor-assistance-app/issues) for existing suggestions
2. If not found, create a new issue with:
   - Clear title describing the feature
   - Detailed description of what you want and why
   - Possible implementation approaches
   - Any relevant examples or mockups

### Submitting Pull Requests

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/donor-assistance-app.git
   cd donor-assistance-app
   ```

2. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Follow the coding standards below
   - Write clean, readable code
   - Add comments for complex logic
   - Include tests for new features

4. **Test your changes**
   ```bash
   npm test
   ```

5. **Commit your changes**
   ```bash
   git commit -m "Add your feature description"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**
   - Link to related issues
   - Describe what your PR does
   - Mention any breaking changes
   - Request review from maintainers

## Coding Standards

### JavaScript/Node.js
- Use ES6+ syntax
- Use `const` by default, `let` when needed
- Use meaningful variable names
- Keep functions small and focused
- Add JSDoc comments for public functions

### React
- Use functional components with hooks
- Follow the single responsibility principle
- Use PropTypes or TypeScript
- Keep components small and reusable
- Use meaningful component names

### Database
- Write clean, optimized SQL queries
- Use proper indexing
- Include migration files for schema changes
- Document complex queries

### General
- Follow existing code style
- Use consistent indentation (2 spaces)
- Remove unused imports and variables
- Keep commits atomic and well-described

## Development Workflow

1. Create a branch from `main` for your feature/fix
2. Make changes and test locally
3. Push to your fork
4. Create a PR against the main repository
5. Wait for review and address feedback
6. Once approved, PR will be merged

## Commit Message Guidelines

- Use clear, descriptive commit messages
- Start with a verb (Add, Fix, Update, Remove, etc.)
- Keep first line under 50 characters
- Add detailed description in body if needed
- Reference issues: "Fixes #123"

Example:
```
Add user authentication endpoint

- Implemented JWT token generation
- Added password hashing with bcrypt
- Created login route with validation
- Added tests for auth flow

Fixes #45
```

## Review Process

All PRs will be reviewed by maintainers. We look for:
- Code quality and correctness
- Test coverage
- Documentation
- Adherence to coding standards
- No breaking changes (unless discussed)

## Code of Conduct

Be respectful and professional:
- Treat all contributors with respect
- No harassment or discrimination
- Focus on constructive feedback
- Help others learn and grow

## Questions?

- Open an issue for questions
- Check existing issues and discussions
- Reach out to maintainers

Thank you for contributing to making donor assistance more accessible! 🙏
