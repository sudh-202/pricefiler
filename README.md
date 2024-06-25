
![pricefilter1](https://github.com/sudh-202/pricefiler/assets/87563365/b2bccffb-e817-4e83-8542-52544f4e0ada)
# A E-commerce Price Tracking Application

# 🤖 Introduction

Developed using Next.js and Bright Data's webunlocker, this e-commerce product scraping site is designed to assist users in making informed decisions. It notifies users when a product drops in price and helps competitors by alerting them when the product is out of stock, all managed through cron jobs.

# ⚙️ Tech Stack

- [Next.js](https://nextjs.org/)
- [Bright Data](https://brightdata.com/)
- [Cheerio](https://cheerio.js.org/)
- [Nodemailer](https://nodemailer.com/)
- [MongoDB](https://www.mongodb.com/)
- [Headless UI](https://headlessui.dev/)
- [Tailwind CSS](https://tailwindcss.com/)


# 🔋 Features

👉 Header with Carousel: Visually appealing header with a carousel showcasing key features and benefits

👉 Product Scraping: A search bar allowing users to input Amazon product links for scraping.

👉 Scraped Projects: Displays the details of products scraped so far, offering insights into tracked items.

👉 Scraped Product Details: Showcase the product image, title, pricing, details, and other relevant information scraped from the original website

👉 Track Option: Modal for users to provide email addresses and opt-in for tracking.

👉 Email Notifications: Send emails product alert emails for various scenarios, e.g., back in stock alerts or lowest price notifications.

👉 Automated Cron Jobs: Utilize cron jobs to automate periodic scraping, ensuring data is up-to-date.
    and many more, including code architecture and reusability.

# 🤸 Quick Start

Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/)
- [npm (Node Package Manager)](https://www.npmjs.com/)

  Cloning the Repository
  
```
 git clone https://github.com/sudh-202/pricefiler.git
 cd pricefiler 
```

Installation

Install the project dependencies using npm:

```
npm install
```

Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

```
#SCRAPER
BRIGHT_DATA_USERNAME=
BRIGHT_DATA_PASSWORD=

#DB
MONGODB_URI=

#OUTLOOK
EMAIL_USER=
EMAIL_PASS=
```
Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these specific websites from BrightData, MongoDB, and Node Mailer.

Running the Project

```
npm run dev
```

# 🔗 Links

[Deploy](https://pricefiler.vercel.app/)

# 🚀 Screenshots
![pricefilter2](https://github.com/sudh-202/pricefiler/assets/87563365/1f5a3d35-75c6-4597-9f91-5e167cd0d989)
![pricefilter3](https://github.com/sudh-202/pricefiler/assets/87563365/475d935f-f2e0-4e6c-ada9-8c0a32302cbe)

