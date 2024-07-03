<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

## Table Of Contents
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#model-architecture-and-training">Model Architecture and Training</a></li>
        <li><a href="#data-and-augmentation-techniques">Data and Augmentation Techniques</a></li>
        <li><a href="#practical-implications">Practical Implications</a></li>
      </ul>
    </li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#step-by-step-guide">Step-by-Step Guide</a></li>
      </ul>
    </li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project
<a id="about-the-project"></a>

This project proposes a deep learning model for classifying eye fundus images into four categories: normal, cataract, diabetic retinopathy (DR), and glaucoma. Leveraging ShuffleNet V2 architecture pretrained on ImageNet, the model is fine-tuned for eye disease classification using a publicly available dataset.

### Model Architecture and Training
<a id="model-architecture-and-training"></a>

ShuffleNet V2, known for its efficiency, was chosen and adapted with additional fully-connected layers. Training involved the Adam optimizer to achieve a test accuracy of 90.41%.

### Data and Augmentation Techniques
<a id="data-and-augmentation-techniques"></a>

Augmentation techniques were tailored to each disease category:
- **Cataract:** Gaussian blur, rotation, and horizontal flipping.
- **Glaucoma:** Grid distortion, rotation, and horizontal flipping.
- **Diabetic Retinopathy (DR):** Pixel dropout, rotation, and horizontal flipping.

### Practical Implications
<a id="practical-implications"></a>

Automated classification of eye fundus images can streamline diagnostics in ophthalmology, facilitating quicker treatment decisions and improving patient outcomes.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- BUILT WITH -->
## Built With
<a id="built-with"></a>

* [OpenCV](https://opencv.org/)
* [scikit-image](https://scikit-image.org/)
* [Matplotlib](https://matplotlib.org/)
* [NumPy](https://numpy.org/)
* [PyTorch](https://pytorch.org/)
* [torchvision](https://pytorch.org/vision/)
* [Albumentations](https://albumentations.ai/)
* [imgaug](https://github.com/aleju/imgaug)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
<a id="getting-started"></a>

### Installation
<a id="installation"></a>

Install the required libraries using the following markdown:

```markdown
- `pip install opencv-python-headless`
- `pip install scikit-image`
- `pip install matplotlib`
- `pip install numpy`
- `pip install torch torchvision`
- `pip install albumentations`
- `pip install imgaug`
```

Ensure all libraries are installed before proceeding with the setup on Kaggle.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

Follow these steps to get started with the project on Kaggle:
Step-by-Step Guide

<a id="step-by-step-guide"></a>

    Download the Notebook:
        Download the Jupyter Notebook (*.ipynb) from the GitHub repository.

    Upload to Kaggle:
        Click on "New Notebook" and choose the option to upload the notebook file.

    Set the Accelerator:
        Once the notebook is uploaded, go to the "Settings" tab.
        Under "Accelerator", select "GPU (P100)" to utilize Kaggle's high-performance GPU for faster computation.

    Run the Notebook:
        Save the settings and run the notebook to train and test your deep learning model.
        Monitor the progress and results directly within the Kaggle notebook environment.

<!-- CONTACT -->

<a id="contact"></a>
Contact

Sparsh Gupta - sparshg2003@gmail.com

Affiliation: Indian Institute of Information Technology, Allahabad

Project Link: https://github.com/sparsh803/Improving_Data_Augementation_Using_Transfer_Learning
<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
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
