# A² Perceptions LLC Website

Static website files for the A² Perceptions LLC public website.

A² Perceptions is developing shared field intelligence for public-safety teams, with an initial focus on search and rescue and future applications across police, EMS, disaster response, and field command.

## Website Structure

The site is currently organized around three primary pages:

### Home — `index.html`

The Home page introduces the company vision and the public-safety problem A² is focused on solving. It presents the core concept of shared field intelligence and highlights the initial SAR-focused capability areas:

- Navigation and wayfinding
- Interview and evidence capture
- Multi-feed intelligence
- Team collaboration

This page also includes the primary hero section, capability visuals, public-safety positioning, and a call to connect with the founders.

### Vision — `vision.html`

The Vision page explains the research-to-commercialization path behind A² Perceptions. It connects the company direction to prior work in shared perception, XR, AI-assisted sensemaking, privacy-aware AR, and distributed SAR collaboration.

The page currently covers:

- The commercial thesis for field-aligned XR guidance
- Research insights from prior publications
- Product implications from that research
- A technical direction focused on hybrid localization, mission-data interoperability, and uncertainty-aware cueing
- A research-to-commercialization timeline
- References to the academic foundation behind the company vision

### About — `about.html`

The About page describes who A² Perceptions is, where the company is located, and why Northern Virginia is a strong place to build public-safety technology.

The page currently covers:

- Northern Virginia location context
- Mission and vision
- Company origin story
- Founder profiles
- Why the region is relevant to SAR, public safety, emergency management, federal stakeholders, and technology partners
- Contact information

## Supporting Files

### Styles

Primary styling is located under:

```text
assets/css/
```

Current page-specific styles may include:

```text
assets/css/styles.css
assets/css/vision-page.css
assets/css/about-page.css
```

`styles.css` contains the shared design system and base layout styles. Page-specific CSS files are used to keep Vision and About changes scoped without unintentionally altering the Home page.

### Scripts

JavaScript files are located under:

```text
assets/js/
```

These files support navigation behavior, scroll effects, and other lightweight front-end interactions.

### Images

Image assets are located under:

```text
assets/img/
```

This folder includes the A² Perceptions logo assets, founder images, and concept visuals used throughout the site.

### Video

Video assets are located under:

```text
assets/video/
```

This folder may include the homepage field-loop background video or related concept media.

## Deployment

This site is designed for GitHub Pages hosting.

Typical deployment flow:

1. Replace or update the relevant files in the repository.
2. Commit the changes to the `main` branch.
3. Ensure GitHub Pages is configured to deploy from the `main` branch and root directory.
4. Wait for GitHub Pages to rebuild and publish the updated site.

## Repository Notes

- The website is static HTML, CSS, JavaScript, images, and video.
- The current navigation includes Home, Vision, About, and Connect With Us.
- The Platform page has been removed from the active navigation.
- Concept visuals are illustrative and represent the product vision, not a finished deployed platform.
- The company is still in an early development stage and the site should be treated as a vision and customer-discovery website rather than a mature product sales page.

## Suggested Editing Practice

When making future updates:

- Avoid changing `index.html` unless the Home page is intentionally being revised.
- Keep page-specific layout changes in page-specific CSS files when possible.
- Preserve the dark tactical design language across pages.
- Keep the content concise, clear, and focused on SAR-first public-safety workflows.
- Avoid adding funding or grant details unless the company intentionally decides to make them public.
