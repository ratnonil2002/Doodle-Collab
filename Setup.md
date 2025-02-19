# React app setup guidelines 🚀

**Hello dev , i want you to stick to the below listed Setup guidelines to successfully setup the react app in your local system and get started with developing!!**

<br/>

- `Fork` the repo to your account.
- `git clone` to clone the repo

- Now you have the repo in your **local storage**
- You can access the `main` folder to get the webapp access
- Next to setup the react app `npm install`


- Create a file named .env in the folder and add the following line, replacing <your_API_endpoint> with the localhost 5000:

```dotenv
VITE_API_URL= <your_API_endpoint>
```

- Once the node modules and other stuffs are installed , `npm run dev` to start the app in `http://localhost:5173/`
- Make changes **according** to the Tasks assigned to you
- Maintain the folder structure , keep small components like **Navbar, Footer** which stays in every page in `src\constants` folder
- keep other small components which stays in every page in `src\components` folder
- Keep big Pages like **Auth page, Home page** in the `src\pages` folder
- Styles of respective pages should be included in respective folder.
- You are also allowed to use GOOGLE FONTS for same fonts as of figma files.
- Other extra **Pictures, icons , svgs** are to be kept in `src\assets\`
- This website will be fully built in MERN Stack i.e MongoDB, ExpressJS, ReactJS, NodeJS.
- Once you are done with the changes , `git pull` to pull the latest version of the code
- `git add .` to stage for commits
- `git commit -s -m "message"` for commiting the code.
- **REMEMBER** --> YOU NEED TO PULL REQ ON `main` BRANCH !!
- Once done create a Pull Request and wait for the mentor to review.
- Don't forget to attach **`Screenshots, Proper Description and Issue Number` in the Pull request**

<br/>


## Development Setup

Please follow the steps below to set up the development environment and contribute effectively.

### 1. Clone the Repository

```bash
git clone https://github.com/goblin45/DoodleCollab-Test
cd DoodleCollab
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the Development Server

```bash
npm run dev
```

Visit [http://localhost:5173](http://localhost:5173) in your browser to run the app.

---

## Server Setup

### 1. Locate the server folder

```bash
cd server
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Setup env file

- Create a file named .env in the server folder and add the following line, replacing <your_mongodb_compass_string> with the copied MongoDB Compass string and replace <your_jwt_secret> with a JWT SECRET:

```dotenv
MONGO_URI=<your_mongodb_compass_string>
JWT_SECRET=<your_jwt_secret>
```

### 4. Run the Server

```bash
npm start
```

Visit [http://localhost:5000](http://localhost:5000) in your browser to run the server of the app.

---