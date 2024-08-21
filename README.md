# Airbnb-Inspired Full-Stack Web Application 🚀

<p align="center">
  
  <br>
  <a style="" href="https://github.com/rajsinghritik">
  <img src="https://profile-counter.glitch.me/Airbnb-project/count.svg" />
  </a>
</p>

---

## Table of Contents

-   [Project Overview](#project-overview)
-   [Technologies & Packages Used](#technologies--packages-used)
-   [Key Features](#key-features)
-   [How to Install](#how-to-install)
-   [Challenges & Solutions](#challenges--solutions)
-   [Special Thanks](#special-thanks)
-   [Author](#author)
-   [Project Link](#project-link)
-   [Thank You](#thank-you)
-   [Ex- Image](#ex--image)

## Project Overview

Excited to share my journey of developing a feature-rich full-stack web application inspired by Airbnb. The project is built using MongoDB, Express.js, and Node.js.

## Technologies & Packages Used

### Backend

-   **MongoDB**: NoSQL database for flexible and scalable data storage.
-   **Express.js**: Web application framework for Node.js, providing robust features for web and mobile applications.
-   **Node.js**: JavaScript runtime for server-side development.

### Authentication

-   **Passport.js**: Middleware for user authentication, supporting various strategies.
-   **Dotenv**: Environment variable management for secure configuration.

### Image Storage

-   **Cloudinary**: Cloud-based image and video management solution.

### Maps

-   **Mapbox**: Platform for custom maps and location-based experiences.

### Frontend

-   **EJS**: Embedded JavaScript templates for dynamic content rendering.

### Session Management

-   **Connect Flash**: Middleware for flash messages.
-   **Connect Mongo**: MongoDB session store for Express.js.
-   **Cookie Parser**: Middleware for parsing cookies.

### Validation

-   **Joi**: Library for data validation.

### Object Modeling

-   **Mongoose**: MongoDB object modeling for Node.js.

### File Uploads

-   **Multer**: Middleware for handling file uploads.

### Social Authentication

-   **Passport Local**: Local authentication strategy.
-   **Passport Facebook**: Facebook authentication strategy.
-   **Passport Google OAuth20**: Google OAuth2.0 authentication strategy.
-   **Passport Local Mongoose**: Mongoose-specific authentication strategy.
    Authentication

## Key Features

-   **User Authentication:** Login, Logout, and User Profile Section
-   **CRUD Operations:** Add, Edit, and Delete Listings
-   **Review System:** Add and Delete Reviews
-   **Account Management:** Update User Account and Password
-   **User Data Security:** Password Hashing and Encryption
-   **Interactive Maps:** Leveraging Mapbox for Location Visualization
-   **Login with Google:** Authenticate with your Google account for a seamless experience
-   **Login with Facebook:** Easily log in using your Facebook credentials
-   **Login with Email:** Traditional email login for user convenience

## How to Install

Follow these steps to set up and run the project locally:

1.  **Clone the Repository:**

    ```bash
    git clone https://github.com/akashdeep023/Airbnb_Project.git
    cd Airbnb_Project
    ```

2.  **Install Dependencies:**

    ```bash
    npm install
    ```

3.  **Set Up Environment Variables:**

    Configure the following environment variables by creating a .env file in the root of your project:

    Example :-

    ```bash
    #https://cloudinary.com/  (Cloudinary) (Change key)
    CLOUD_NAME=kjkdmckdhjks
    CLOUD_API_KEY=89340593499490394
    CLOUD_API_SECRET=jdskLKJlklkdlsdfkKKdsdkkd

    #https://www.mapbox.com/ (Mapbox)
    MAP_TOKEN=pk.eyJ1IjoiZGVsdGEtc3R1ZHVlbnQiLCJhIjoiY2xvMDk0MTVhMTJ3ZDJrcGR5ZDFkaHl4ciJ9.Gj2VU1wvxc7rFVt5E4KLOQ

    #https://www.mongodb.com/ (MongoDb Atlas) (Change key)
    ATLASDB_URL=mongodb+srv://demo:kLKJFKOEMNDDOI9089dndd@cluster0.kkdnvkdkds.mongodb.net/?retryWrites=true&w=majority

    #Add Random Secret Key
    SECRET=ckcdenlksufoifafknddsoiddfkadsfafd

    #https://console.developers.google.com/ (Google Developer Console) (Change key)
    GOOGLE_CLIENT_ID=89038948394-kjfdkcmckdmckdfsid94jkkknd9sd4.apps.googleusercontent.com
    GOOGLE_CLIENT_SECRET=KDJKDF-4KJDF894NF-DFKEF9MN-NFKEJD

    #https://developers.facebook.com/ (Facebook Developer Console) (Change key)
    FACEBOOK_APP_ID=94383859383287
    FACEBOOK_APP_SECRET=89diodfjd9r98ddfjsodwj9df8d

    #Add redirect URL in Google Developer Console
    GOOGLE_CALLBACK_URL=http://localhost:8080/auth/google/callback

    #Add redirect URL in Facebook Developer Console
    FACEBOOK_CALLBACK_URL=http://localhost:8080/auth/facebook/callback

    ```

    Replace the values with your specific configurations.

4.  **Run the Application:**

    ```bash
    node app.js
    ```

5.  **Open in Your Browser:**

    Open `http://localhost:8080/listings` in your web browser.

## Challenges & Solutions

Encountered challenges, especially with data handling, but implemented efficient solutions. Overcame scalability issues with a well-architected backend.

## Special Thanks

A heartfelt thank you to Shradha Khapra didi and AMAN DHATTARWAL bhaiya at #ApnaCollege for their invaluable support and collaboration. As mentors and teachers, your guidance has been instrumental in shaping the success of this project. Your dedication to fostering learning and innovation has made a lasting impact, and I'm grateful for the opportunity to learn and grow under your mentorship.

## Author :
   Ritik Raj
   <br>
   Email: rajsinghritik@gmail.com
   <br>
   LinkedIn : linkedin.com/in/ritikraj8
## Website Link :
   url : https://github.com/rajsinghritik/Amazon-Clone/


## Thank You

Thank you for exploring Airbnb! Your feedback is valuable. If you have any suggestions or thoughts, feel free to share them with us. 😊

---

## Ex- Image

##Home Page
![312038127-4277d539-f779-48db-92ca-222be5359baa](https://github.com/user-attachments/assets/51371965-3a85-4443-b68d-3c2bca67d01c)

**Footer Page**
![312038463-84f6e124-91aa-4dd9-b14b-d67781effe33](https://github.com/user-attachments/assets/3e8d6e8b-6637-4fe2-b8aa-77e271066341)

**SignUp Page**
![312038741-d8753ac5-b237-4373-850c-99008137af5b](https://github.com/user-attachments/assets/18f1775d-4c6a-45c4-9813-dc304e1fa5d5)

**LogIn Page**
![312038997-5bec0280-c4de-495d-93ac-1f9ae59df0c3](https://github.com/user-attachments/assets/a6d34696-0499-4cdd-a605-e123cd74690e)


**Profile Page**


**Update Prifile**


**Confirmation Box**

**Alert Msg**
ffc)
![312040570-70b4f767-fba9-4bc2-b0f1-efb700cc1cc3](https://github.com/user-attachments/assets/86086975-96a1-402f-915e-391eedc9e449)
![312039946-b6857746-bdb7-4655-91bc-58deebe5bffc](https://github.com/user-attachments/assets/247975e6-9fe2-4008-858e-968793f3db1e)

**Loader**
![312046084-fad03cbb-fac8-463a-a09d-d871e87ad474](https://github.com/user-attachments/assets/fcb2954f-842a-413b-ae71-782810f1a28d)

**Create New Restaurant**

![312042389-bb3cc8be-5cf2-4902-8f34-948cda8a58e7](https://github.com/user-attachments/assets/bd49e1d7-e747-4050-a4a0-1c69fa16e6bf)
![312042490-db343223-2996-489c-9089-d00238074970](https://github.com/user-attachments/assets/d0635ecd-da60-432b-b6f7-bcfae2082934)

**Show Page**

![312042860-dc9b64d3-9348-4b6f-84c4-319b19df3aff](https://github.com/user-attachments/assets/a247654d-5181-40a7-8866-8f3722a90c52)
![312043430-a2c161da-cebd-4154-b26b-45f4da77c4cb](https://github.com/user-attachments/assets/1e179cbf-9674-4534-9888-911b01dedd30)

**Edit Page**
![312043430-a2c161da-cebd-4154-b26b-45f4da77c4cb](https://github.com/user-attachments/assets/1d66beba-331c-47b5-bc93-42fb541e73e8)
![312043632-0667a6ee-5136-460e-ae6f-c64bd9859388](https://github.com/user-attachments/assets/a48af8e4-b44f-4057-a7e3-b3f0b970cdbe)
![312043713-60113611-b7ab-40df-a29a-75d32a49671c](https://github.com/user-attachments/assets/d354a901-1ba7-4423-80ea-bd045369aacc)

**Filter Page**
![312043955-6df98108-a1fc-462c-bda6-cf7563b6027e](https://github.com/user-attachments/assets/52fe2673-13f4-4861-9530-51e81f1d7e37)
![312044077-c8ff9e97-739e-44c4-8303-ca96b1153eec](https://github.com/user-attachments/assets/60e36eba-cb5e-4cfe-962c-3ab70ef2730d)


### Thanks for visit... 😊😊😊
