<!--
*** Thanks for checking out this README Template. If you have a suggestion that would
*** make this better, please fork the repo and create a pull request or simply open
*** an issue with the tag "enhancement".
*** Thanks again! Now go create something AMAZING! :D
-->





<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
![GitHub contributors](https://img.shields.io/github/contributors/roverzealous/PowerShell)
![GitHub forks](https://img.shields.io/github/forks/roverzealous/PowerShell)
![GitHub stars](https://img.shields.io/github/stars/roverzealous/PowerShell)
![GitHub issues](https://img.shields.io/github/issues/roverzealous/PowerShell)

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [Code](#code)
* [Contact](#contact)



<!-- ABOUT THE PROJECT -->
## About The Project

A collection of Modules and Scripts we use in PowerShell

<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<!-- CODE -->
## Code

-[**Client**](https://github.com/roverzealous/Public-PowerShell/tree/master/Client)
 -[**Start-Sync Module**](https://github.com/roverzealous/Public-PowerShell/blob/master/Client/Start-Sync.psm1)

  -*This module will copy what ever folders you set. We use this to edit our PowerShell Profiles and then sync them across all                 profile locations.*

    Function Start-Sync {
        robocopy C:\FolderToCopyFrom\ C:\FolderToCopyTo\ /E /MIR
    }



<!-- CONTACT -->
## Contact

Ryan Johnson - [@roverzealous](https://twitter.com/roverzealous)

Project Link: [https://github.com/roverzealous/PowerShell](https://github.com/roverzealous/PowerShell)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
