# Troubleshooting

[Return to Home Page](https://github.com/rohankane22/PRWR623-Project-1)

Some problems arise more commonly while installing spaceKLIP; this page is intended to provide answers to questions that arise naturally in the course of the installation process.

**During a pip install, a package was not successfully installed**

If your command line reads "Attempting to build wheel for [package]" and proceeds to an error message, you may instead need to directly install this package using conda. Parse through the error message to find which version pip was was attempting to install, and in the command line enter

    conda install [package] --version=[version number]