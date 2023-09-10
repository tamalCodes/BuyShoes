<!-- TOC -->

- [Project Details 💼](#project-details-)
  - [What is this project about ?](#what-is-this-project-about-)
  - [What are the technologies used ?](#what-are-the-technologies-used-)
  - [Working Demo](#working-demo)
- [Setup Instructions 📖](#setup-instructions-)
  - [Frontend 🚀](#frontend-)
  - [Backend 🚀](#backend-)
    - [`develop`](#develop)
    - [`start`](#start)
    - [`build`](#build)
    - [⚙️ Deployment](#️-deployment)
    - [📚 Learn more](#-learn-more)

<!-- /TOC -->

# Project Details 💼

## What is this project about ? 

This project is basically an e-commerce platform that is used to buy different kinds of shoes online. The user can select their particular size of shoes and then add it to the cart and after that, they can choose the number of products they want and finally, they can place their order and purchase it.

## What are the technologies used ?

The technologies used in this project are as follows:

1. **`Next.js`** --> It is a React framework that is used to build the frontend of the application.Leverages React's server-side rendering capabilities and huge out-of-the-box features like file-based routing, API routes, and more. <br/><br/>
2. **`Tailwind CSS`** --> It is a utility-first CSS framework that is used to style the application. It is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override. <br/><br/>
3. **`Strapi`** --> It is a headless CMS that is used to build the backend of the application. It is an open-source, self-hosted, and customizable content management system (CMS) that is built with Node.js and React. It is a fully open-source JavaScript-based, and frontend-agnostic headless CMS. <br/><br/>
4. **`Cloudinary`** --> It is a cloud-based image and video management service that is used to store the images of the products. It is a cloud-based image and video management service that allows you to upload, store, manage, manipulate, and deliver images and video for your websites and apps. <br/><br/>
5. **`Stripe`** --> It is a payment processing platform that is used to make the payment. In this case we are using it so that the users can make their orders after buying the products. <br/><br/>
6. **`Postegresql`** --> It is a relational database management system that is used to store the data of the users. It is a free and open-source relational database management system emphasizing extensibility and SQL compliance. <br/><br/>

## Working Demo

---

# Setup Instructions 📖


## Frontend 🚀

Install the dependencies & start the development server (frontend)

```bash
npm install
npm run dev
```

## Backend 🚀

Change the directory to the backend and then install the dependencies 

```bash
cd server
npm install
```

Strapi comes with a full featured [Command Line Interface](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html) (CLI) which lets you scaffold and manage your project in seconds. Do one of the following

### `develop`
Start your Strapi application with autoReload enabled. **Recommended for Development** [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```bash
npm run dev
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```bash
npm run start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```bash
npm run build
```

### ⚙️ Deployment

Strapi gives you many possible deployment options for your project. Find the one that suits you on the [deployment section of the documentation](https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/deployment.html).

### 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!
