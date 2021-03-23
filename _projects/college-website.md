---
layout: project
name: College Website Theme
permalink: /projects/college-website/
description: |-
  Quickly get start with building
  college website.<br>Fork the GitHub project.
  Clone the project in your machine.
  Customize the website as per your needs.
  Deploy the website.
# preview:
#   youtube:
#     id: GF97vqJWwCs

header-text: College Website Theme
---

# About College Website Theme

The _College Website Theme_ is a [Jekyll](https://jekyllrb.com){:target="_blank"} based template
for building college website quickly.

The theme has been designed in a way that it can be developed and maintained even by
_college students_.

## Getting Started

This section will help you with setting up your development environment for building college website theme.

### Prerequisites

#### 1. Install Ruby language

##### 1.a) Install Ruby in Windows

- Visit [RubyInstaller](https://rubyinstaller.org/downloads/){:target="_blank"}
  downloads page and click on `Ruby+Devkit 2.7.1-1 (x64)`.

  __NOTE:__ If you have 32 Bit machine, install `Ruby+Devkit 2.7.1-1 (x86)`.

- Open the binary and install it
- Open command or powershell prompt and verify

  ```shell
  ruby -v
  ```

##### 1.b) Install Ruby in Linux or macOS

_NOTE:_ This method is preferred as we have experienced many issues while using System's Ruby that comes by default.

- Visit [RVM website](https://rvm.io/){:target="_blank"}
- Install GPG Keys
- Install Ruby

  ```shell
  \curl -sSL https://get.rvm.io | bash -s stable
  ```

- Run the "source" command which you get at the end of above install command.
  It will look similar as highlighted in the screenshot.

  ```shell
  source ~/.rvm/scripts/rvm
  ```

  <img src="/assets/img/ruby-install-source.jpg" class="img-fluid" alt="loading ...">

- Verify your installation by checking the version

  ```shell
  ruby -v
  ```

  and make sure it is the same Ruby version which you installed via RVM

#### 2. Install Jekyll Framework

Run the following command to install Jekyll in your machine

```shell
gem install bundler jekyll
```

and verify by running following command

```shell
jekyll -v
```

#### 3. Clone project repository

Run the following command to clone the repository:

```shell
git clone https://github.com/brgclasses/college-jekyll
cd college-jekyll
```

#### 4. Run the project locally

Now you are ready with all the prerequisites required for running the project.

- Run the following command to install required gems (or packages)

  ```shell
  bundle install
  ```

- Run the following command to start the Jekyll server

  ```shell
  bundle exec jekyll serve
  ```

- Open the server url [http://localhost:4000](http://localhost:4000) in your browser.
