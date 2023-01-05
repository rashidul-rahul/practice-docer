# Practice-docker
Just trying to make a docker file for a python django project
[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
[![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
[![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

## Installation

Need to install this program on your system

```bash
  python3
  docker
```

## Run Locally

Clone the project

```bash
  git clone https://github.com/rashidul-rahul/practice-docer.git
```

Go to the project directory

```bash
  cd practice-docer
```

Buid docker image

```bash
  docker build --tag python-dajngo .
```

Run docker file

```bash
  docker run --publish 8000:8000 python-dajngo
```