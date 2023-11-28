The below README provides a comprehensive template for any of future repos. 
Fork this repo to create a copy for yourself and select the sections that you find relevant for your repo.👇

_If you find this template useful, consider giving it a star_ 🙏


---

<p align="center">
    <!--     You can add your logo here -->
    <img src="https://www.amug.com/wp-content/uploads/2016/09/you-logo-here-300x106.png" />
</p>
<p align="center">
  <!-- You can add your badges here -->
  <!-- If you have never added badges, head over to https://img.shields.io/badges/static-badge, follow the instructions and generate URL links to add below -->
  <img src="https://img.shields.io/badge/STARS-20K-green"  />
  <img src="https://img.shields.io/badge/FORKS-15K-blue"  />
  <img src="https://img.shields.io/badge/npm-v.0.21.0-red"  />
  <img src="https://img.shields.io/badge/LICENSE-MIT-green"  />
</p>


### :star2: About
- Write a short introduction to the project.
- Try to keep it concise ➡️ think 2-4 sentences.


### :books: Index

- [About](#star2-About)
- [Demo](#movie_camera-Demo)
- [Set Up](#outbox_tray-Set-up)
- [Contribute](#building_construction-Contribute)
- [Deployment](#rocket-Deployment)
- [File Structure](#file_folder-File-Structure)
- [Roadmap](#bicyclist-Roadmap)
- [FAQ](#thinking-FAQ)
- [License](#page_facing_up-License)
- [List of Contributors](#people_holding_hands-Our-List-of-Contributors)
- [Contact](#email-contact)


###  :movie_camera: Demo
- After the initial introduction, you can add a screen recording of your project.
- If the video's size is too large, it is a good idea to post your video on YouTube and attach a picture that redirects to the video (as shown below).

<p align="center">
    <a href="https://youtu.be">
        <img src="https://private-user-images.githubusercontent.com/83458751/286227027-bd7c3b93-0c32-4fdf-bf6d-01d6114633ad.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDEyMDEzODYsIm5iZiI6MTcwMTIwMTA4NiwicGF0aCI6Ii84MzQ1ODc1MS8yODYyMjcwMjctYmQ3YzNiOTMtMGMzMi00ZmRmLWJmNmQtMDFkNjExNDYzM2FkLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFJV05KWUFYNENTVkVINTNBJTJGMjAyMzExMjglMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjMxMTI4VDE5NTEyNlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWUwOGI3M2MxMWNlZTM4MTVjMDM1YmEwOGExNjA5MTgwYTVjZjdlMTdlMTdhYzBiMWQyODhjMDc5NzRjZTEyNWImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.i08EtN_6rjsrrr6n-MNBkQPyOSocTunJpcXK2PU9gOM"/>
    </a>
</p>


$~$

###  :outbox_tray: Set up
- These are the steps required to install the project.
- Mention, if needed, requirements based on the different OS type: `<Windows/Linux/Mac>`.

_E.g_

1. Get a API Key at [website](example.com)
2. Clone the repo
   ```sh
   git clone https://github.com/YOUR_USERNAME/Project-Name.git
   ```
3. Install NPM packages
   ```sh
   npm install npm@latest -g
   ```
4. Enter your API in `config.js`
   ```js
   const API_KEY = 'YOUR API KEY HERE';
   ```

$~$

###  :building_construction: Contribute

- In this section, you invite users to learn how to contribute to your project.
- This is also the place to add a link to your CONTRIBUTING.md file

  _E.g_

**Choose an Issue**

1. Pick an issue that interests you - if you're new, look for `good-first-issue` tags.
2. Read the CONTRIBUTING.md file
3. Comment on the Issue, and explain why you want to work on it
   You can showcase any relevant background information on why you can solve the issue.
    
**Set Up Your Environment**

1. `Fork` our repository to your GitHub account. 
2. `Clone` your fork to your local machine. 
    Use the command `git clone <your-fork-url>`.
3. Create a new branch for your work. 
    Use a descriptive name, like `fix-login-bug` or `add-user-profile-page`.
    
**Commit Your Changes**

- Commit your changes with a _clear commit message_. 
  e.g `git commit -m "Fix login bug by updating auth logic"`.

**Submit a Pull Request**

- Push your branch and changes to your fork on GitHub.
- Create a pull request, compare branches and submit.
- Provide a detailed description of what changes you've made and why. 
  Link the pull request to the issue it resolves. 🔗
    
**Review and Merge**

- Our team will review your pull request and provide feedback or request changes if necessary. 
- Once your pull request is approved, we will merge it into the main codebase 🥳

$~$

### :rocket: Deployment
- You can write your deployment instructions here.

$~$

###  :file_folder: File Structure

- Adding a file structure can help users gain a high-level understanding of your project. 
- If your project has too many files, you can consider showcasing only the main folder paths. 

```
.
├── client
│   ├── public
│   │   ├── favicon.ico
│   │   └── index.html
│   ├── src
│   │   ├── App.css
│   │   ├── App.js
│   │   ├── index.js
│   │   └── logo.svg
│   └── package.json
├── server
│   ├── controllers
│   │   └── userController.js
│   ├── models
│   │   └── userModel.js
│   ├── routes
│   │   └── userRoutes.js
│   ├── app.js
│   └── package.json
├── .gitignore
├── LICENSE
└── README.md
```

### :bicyclist: Roadmap
_Current version number_
- [x] Introduction of Concept
- [x] Feature 1
- [ ] Feature 2
- [ ] Revisit Feature 1
    - [ ] Improve XYZ
    - [ ] Revamp CSS

$~$

### :thinking: FAQ
Something that works quite well if you want to include an FAQ  here are **toggle lists.** 

<details>
  <summary>Toggle List Example</summary>
  
  ### Title
  1. ABC
  2. DEF
     * Hello
     * Bye

  ### Here's the MARKDOWN template to build your own toggle lists
  ```
    <details>
    <summary>Toggle List Example</summary>
    
    ### Heading
    1. ABC
    2. DEF
       * Hello
       * Bye
    </details>
  ```

</details>

$~$

### :page_facing_up: License
- State the license chosen and link it here.
- You can also provide a justification for the type of license chosen if you believe it to be necessary.

$~$

### :people_holding_hands: Our List of Contributors
- State all the contributors that have helped build this project.
- You can use the bot made by [https://allcontributors.org/](https://allcontributors.org/) to add new contributors automatically.
- Here's an example of what you can have with _allcontributors.org_:

<img width="940" alt="contributors-table-small" src="https://github.com/quine-sh/README-Template/assets/83458751/7e93c398-24d1-40e7-992c-ec4a3c413ed7">


### :email: Contact 
- Email and social media links.
- Head over to [[https://github.com/alexandresanlim/Badges4-README.md-Profile](https://github.com/alexandresanlim/Badges4-README.md-Profile#-social-)
  * Copy paste the social links you enjoy and drop them below (make sure to change the `href` to your own links

<p align="left">
<a href="https://twitter.com/fernandezbap" target="blank"><img align="center" src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="fernandezbap" /></a>
</p>
<p align="left">
<a href="https://www.linkedin.com/in/baptiste-fernandez-%E5%B0%8F%E7%99%BD-0a958630/" target="blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"  /></a>
</p>




