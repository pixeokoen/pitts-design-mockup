# Project Practices & Guidelines

## PITTS Design Mockup - Development Guidelines

This document outlines the key practices and guidelines for managing the PITTS (Pigeons Into The Sky) design mockup project.

---

## 🚨 Git & Version Control Rules

### **Rule #1: No Automatic Commits/Pushes**
**CRITICAL**: Never automatically commit and push changes without explicit confirmation from the project owner.

- Always ask for confirmation before running `git commit` or `git push`
- Present changes clearly and wait for approval
- Only commit when explicitly requested
- This ensures full control over what goes into the repository

### Git Workflow
1. Make changes to files as requested
2. Show/explain what was changed
3. **WAIT** for explicit confirmation to commit
4. Only then run `git add .`, `git commit`, and `git push`

---

## 📁 Project Structure Guidelines

### Documentation Standards
- Keep all documentation in the `_docs/` folder
- Use clear, descriptive filenames
- Follow markdown formatting standards
- Update relevant docs when making changes

### Asset Organization
- Logo files: `assets/images/logo/`
- Icons: `assets/icons/`
- Create folders as needed, no .gitkeep files
- Use web-optimized formats (WebP, SVG preferred)

---

## 🎨 Development Standards

### Technology Stack
- **Frontend**: HTML5, Tailwind CSS, Alpine.js
- **Icons**: Lucide Icons (functional only, no decorative)
- **Approach**: Component-thinking for future Laravel/Alpine.js migration
- **Language**: Dutch content for pigeon racing community

### Code Quality
- Use semantic HTML structure
- Implement accessibility standards (AA/AAA compliance)
- Mobile-first responsive design

---

## 🔄 Change Management

### Before Making Changes
1. Load and read reference documents first
2. Confirm understanding of requirements
3. Plan changes according to established guidelines

### After Making Changes
1. Test functionality thoroughly
2. Explain what was changed and why
3. **WAIT** for approval before committing
4. Only commit when explicitly requested

---

## 📋 Communication Guidelines

### Status Updates
- Explain changes clearly and concisely
- Ask for clarification when requirements are unclear
- Provide context for technical decisions

### Error Handling
- Report issues immediately
- Provide clear error descriptions
- Suggest solutions when possible
- Never hide problems or make assumptions

---

## 📚 Design System Documentation

### **Rule #2: Maintain Documentation Consistency**
**CRITICAL**: Any changes to imports, libraries, stylesheets, or components in the main mockup MUST be reflected in the design documentation site.

### Documentation Synchronization Requirements
1. **Technology Stack Changes**: If CDN links, library versions, or dependencies change in `index.html`, update `design-docs/index.html` accordingly
2. **Component Updates**: When modifying components in the main mockup, update the corresponding documentation page with:
   - Updated code examples
   - New configuration options
   - Changed behavior or styling
3. **Style Changes**: CSS modifications, Tailwind config changes, or custom styles must be synced to documentation
4. **New Components**: Every new component created in the mockup gets its own documentation page with:
   - Live preview
   - Copy-paste ready code
   - Usage guidelines
   - Configuration options

### Documentation Structure
- **Main Site**: `design-docs/index.html` - Professional documentation site
- **Component Pages**: Individual documentation for each component
- **Live Previews**: Working examples using the same tech stack
- **Code Examples**: Copy-paste ready HTML and Alpine.js code
- **Usage Guidelines**: Implementation instructions for dev team

### Workflow for Component Changes
1. Make changes to component in main mockup
2. Test changes thoroughly
3. Update corresponding documentation page
4. Verify live preview works correctly
5. Update code examples and usage notes
6. Only then commit all changes together

---

## 🎯 Project Goals

### Primary Objectives
- Create professional mockup for PITTS platform
- Build comprehensive design system documentation
- Prepare codebase for Laravel/Alpine.js migration
- Maintain brand consistency and user experience
- Support Dutch pigeon racing community needs
- Enable easy component reuse for dev team

### Quality Standards
- Clean, maintainable code
- Responsive design across all devices
- Fast loading times
- Accessibility compliance
- Professional appearance
- Complete documentation coverage

---

*Last updated: January 2025*
*This document should be updated as new practices are established.* 