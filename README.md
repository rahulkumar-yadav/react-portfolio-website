# React Portfolio Website

This project is a responsive portfolio website built using React.js. It includes various sections such as Hero, About, Services, Skills, Projects, Timeline, Testimonial, and Contact Form. The data for these sections is fetched from an external API endpoint provided.

## Live Demo

You can view a live demo of the project [here](https://react-portfolio-website-project.netlify.app/).

## Task Description

The task involved creating a portfolio website with the following sections:

- Hero
- About
- Services
- Skills
- Projects (with custom modal)
- Timeline (divided into Education and Experience)
- Testimonial (Auto Slide format)
- Contact Form

## Data Integration

Data is fetched dynamically from the provided API endpoint and integrated into the respective sections of the portfolio. The sections are filtered based on the "enabled" field from the API response.

### Sections and Data Integration:

- **Hero and About:** Data from the "about" field.
- **Services:** Data from the "services" field.
- **Skills:** Data from the "skills" field.
- **Projects:** Data from the "projects" field, with a custom modal for detailed project overview.
- **Timeline:** Divided into Education and Experience based on the "forEducation" field.
- **Testimonials:** Auto slider implemented for the Testimonials section.
- **Contact:** Relevant data such as address, email, and phone number from the "about" field, along with a custom contact form.

## Implementation

The project exceeds the quality level of the provided sample portfolio by at least fivefold. Advanced features such as filtering projects based on tech stack and sorting them by sequence are implemented. Animations using libraries like Framer Motion, GSAP, etc., are incorporated to enhance the user experience and make the portfolio visually appealing.

## Getting Started

To get a local copy up and running, follow these steps:

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the development server using `npm start`.

## Technologies Used

- React.js
- Framer Motion
- GSAP
- etc. (list any additional libraries used)

## Getting Started

To run this project locally, follow these steps:

1. Clone the repository to your local machine:

```
git clone https://github.com/rahulkumar-yadav/react-portfolio-website.git
```

2. Navigate to the project directory:

```
cd react-portfolio-website
```

3. Install dependencies:

```
npm install
```

4. Run the development server:

```
npm run dev
```

This will start the development server, and you can view the webpage by accessing http://localhost:3000 in your browser.

Thank you for checking out my project!
