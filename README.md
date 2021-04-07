# Ultimate Vocal Remover v5 Command Line Beta

## About

This application is a heavily modified version of the vocal remover AI created and posted by GitHub user [tsurumeso](https://github.com/tsurumeso). You can find tsurumeso's original command line version [here](https://github.com/tsurumeso/vocal-remover). The official v5 GUI is still under developement and will be released some time in Q3 2021. New models for this version will be released at the end of the week.

- **Special Thanks**
    - [tsurumeso](https://github.com/tsurumeso) - The engineer who authored the AI code. Thank you for the hard work and dedication you put into the AI application this GUI is built around!
    - [aufr33](https://github.com/aufr33) - Model collaborator and fellow UVR developer. This project wouldn't be what it is without your help, thank you for your continued support!
    - [DilanBoskan](https://github.com/DilanBoskan) - The main GUI code contributor. Thank you for helping bring this GUI to life! Your hard work and continued support is greatly appreciated.

## Installation

### Install Required Applications & Packages

```
pip install --no-cache-dir -r requirements.txt
pip install torch==1.6.0+cu101 torchvision==0.7.0+cu101 -f https://download.pytorch.org/whl/torch_stable.html
```

### FFmpeg 

FFmpeg must be installed and configured in order for the application to be able to process any track that isn't a *.wav* file. Instructions for installing FFmpeg can be found on YouTube, WikiHow, Reddit, GitHub, and many other sources around the web.

- **Note:** If you are experiencing any errors when attempting to process any media files that are not in the *.wav* format, please ensure FFmpeg is installed & configured correctly.

### Running the Vocal Remover GUI & Models

***Coming Soon***

## Option Guide

***Coming Soon***

## Models Included

All of the models included in the release were trained on large datasets containing diverse sets of music genres.

Here's a list of the models included within the package -

***Coming Soon***

A special thank you to aufr33 for helping me expand the dataset used to train some of these models and for the helpful training tips.

## Troubleshooting

### Common Issues

- This application is not compatible with 32-bit versions of Python. Please make sure your version of Python is 64-bit. 
- If FFmpeg is not installed, the application will throw an error if the user attempts to convert a non-WAV file.

### Issue Reporting

Please be as detailed as possible when posting a new issue. Make sure to provide any error outputs and/or screenshots/gif's to give us a clearer understanding of the issue you are experiencing.

If you are unable to run conversions *under any circumstances* and all other resources have been exhausted, please do the following - 

1. Copy and paste the error output shown in the cmd prompt to the issues center on the GitHub repository.

## License

The **Ultimate Vocal Remover GUI** code is [MIT-licensed](LICENSE). 

## Contributing

- For anyone interested in the ongoing development of **Ultimate Vocal Remover** please send us a pull request and we will review it. This project is 100% open-source and free for anyone to use and/or modify as they wish. 
- We only maintain the development and support for **Ultimate Vocal Remover** and the models provided. 

## References
- [1] Takahashi et al., "Multi-scale Multi-band DenseNets for Audio Source Separation", https://arxiv.org/pdf/1706.09588.pdf
