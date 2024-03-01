<!-- Improved compatibility of back to top link: See: https://github.com/sbalot/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/sbalot/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">SHACL Shapes DataBase</h3>

  <p align="center">
   A database of SHACL constraints for checking conformance of meta-data of heterogeneous resources in AEC projects
    <br />
    <a href="https://github.com/sbalot/Best-README-Template"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/sbalot/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/sbalot/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/sbalot/Best-README-Template/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This repository contains all the SHACL Shapes created as a part of the BIM4Ren project and my PhD thesis. All shapes are modularized and contain namespaces used in the thesis. The aim of this database is to facilitate reuseable SHACL shapes for automated checking of Linked Building Data in AEC projects. The SHACL Shapes can be used for checking conformance of the following types of resources:

* Meta-data of partial Linked Building Data
* Annotation Meta-data of Images & Documents
* Information container-related meta-data
* Link relationships and their provenances

The ontologies used in the SHACL shapes belong to both the Upper/Foundational Ontologies and Domain Ontologies. For concepts with multiple commonly available terminologies from different ontologies, the SHACL shapes were framed to be applicable, regardless of the ontology used. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>


### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* MS Code

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Below are the steps for using the SHACL Shapes for checking resource conformity.

### Prerequisites

Installation of any SHACL Validation program (either on local machine as a library or use an online service.

Popular validation engines are: 
* https://shacl.org/playground/
* https://shacl-play.sparna.fr/play/
* https://jena.apache.org/documentation/shacl/
* https://www.npmjs.com/package/rdf-validate-shacl
* https://www.itb.ec.europa.eu/shacl/any/upload

Depending on the validation program chosen, follow the isntructions for using the shapes from this database

### Installation

_Below is an example of using SHACL PLAYGROUND (https://shacl.org/playground/) for validation_

1. Select a Shapes Graph from the /Shapes folder in this repo. 
2. Select an Instance Graph from your own database, or use an example form the /Data folder in this repo.
3. Upload both these graphs in the appropriate spaces in a validator engine.
4. Click on ```Update``` button for viewing the validation result.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Madhumitha Senthilvel - [@your_twitter](https://twitter.com/your_username) - madhusvel@gmail.com

Project Link: [https://github.com/sbalot/BIM4Ren_SHACLDB](https://github.com/sbalot/BIM4Ren_SHACLDB)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [BIM4Ren Research Project](https://bim4ren.eu/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/sbalot/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/sbalot/README/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/sbalot/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/sbalot/README/network/members
[stars-shield]: https://img.shields.io/github/stars/sbalot/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/sbalot/README/stargazers
[issues-shield]: https://img.shields.io/github/issues/sbalot/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/sbalotREADME/issues
[license-shield]: https://img.shields.io/github/license/sbalot/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/sbalot/README/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/madhumithasenthilvel
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
