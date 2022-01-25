<div id="top"></div>


<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/othneildrew/Best-README-Template">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">Zero-To-Hero</h3>

  <p align="center">
    A repo that represents my homelab using Infrastructure as Code
    <br />
    <!-- <a href="https://github.com/othneildrew/Best-README-Template"><strong>Explore the docs »</strong></a> -->
    <!-- <br />
    <br />
    <a href="https://github.com/othneildrew/Best-README-Template">View Demo</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a> -->
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<!-- <details>
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
</details> -->



<!-- ABOUT THE PROJECT -->
## About The Project

<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com) -->

Creating and destroying VMs and containers for my proxmox server is always a chore. I never remember what state I left things in, how the networking is configured, what Java versions I have installed, etc. etc.

While Proxmox lets you spin up VMs easily with an ISO, going through the manual installation process is a pain.

As many linux distributions come with pre-built cloud-init ready images, I'd like to streamline the creation of base images that I can then use to create template VMs. Some users have already figured out how to do most of this with some bash scripts while sshing to the Proxmox server, but I would prefer to only use the API and stay away from tinkering from a root shell on my Proxmox host.

Regardless of my pace for this project, everything needs to be IaC so that I can return to it at any time. I should be able to destroy all VMs/images/resources on the proxmox server and simply recreate them with a single script.

<p align="right">(<a href="#top">back to top</a>)</p>



### Tech used

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Proxmox](https://nextjs.org/)
* [Python](https://reactjs.org/)
* [k3s](https://vuejs.org/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

* TBD

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.
* Have a Proxmox server
* Docker installed locally



<!-- ROADMAP -->
## Roadmap

- [ ] Automate creating a cloud-init template for Proxmox (minimal OS template)
- [ ] Setup Packer to automatically build k8s configured VM templates
- [ ] Setup k8s
  - [ ] Auto-scaling?
  - [ ] small app/service
- [ ] Jenkins X


<!-- See the [open issues](https://github.com/othneildrew/Best-README-Template/issues) for a full list of proposed features (and known issues). -->

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
<!--## Contributing

 Contributions are welcome! 

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request -->

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
<!-- ## Contact

Project Link: [https://github.com/wuillaumea/zero-to-hero](https://github.com/wuillaumea/zero-to-hero) -->

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [README Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[stars-url]: https://github.com/othneildrew/zero-to-hero/stargazers
[license-shield]: https://img.shields.io/github/license/wuillaumea/zero-to-hero.svg?style=for-the-badge
[license-url]: https://github.com/wuillaumea/zero-to-hero/blob/main/LICENSE
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/alex-wuillaume-955135134/
[product-screenshot]: images/screenshot.png