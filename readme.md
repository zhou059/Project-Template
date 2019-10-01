# Repo Title _(alternative Repo Name)_
<!-- 
    This should be identical to the repository name/project name, or a relevant title, with the repo name in the italicized paranthesis. The repo name should be in this title is what I'm gettin at here.
-->
![Repository Banner](/images/RepoLogo)
<!-- Optional. This should be sourced from your repository locally. No text needed. 
-->

[![build passing](https://img.shields.io/badge/build-passing-green.svg)]()

[![Salesforce API v46.0](https://img.shields.io/badge/Salesforce%20API-v46.0-blue.svg)]()

[![Lightning Experience Required](https://img.shields.io/badge/Lightning%20Experience-Required-informational.svg)]()
[![Lightning Experience Required](https://img.shields.io/badge/Lightning%20Experience-Not%20Required-inactive.svg)]()

[![User License Sales](https://img.shields.io/badge/User%20License-Sales-3d867d.svg)]()
[![User License Sales](https://img.shields.io/badge/User%20License-Service-7f2443.svg)]()
[![User License Sales](https://img.shields.io/badge/User%20License-Communities-ffc20e.svg)]()
[![User License Sales](https://img.shields.io/badge/User%20License-Platform-032e61.svg)]()
[![User License Sales](https://img.shields.io/badge/User%20License-None-818181.svg)]()

[![Apex Test Coverage 100](https://img.shields.io/badge/Apex%20Test%20Coverage-100-brightgreen.svg)]()
[![Apex Test Coverage 83](https://img.shields.io/badge/Apex%20Test%20Coverage-83-yellowgreen.svg)]()
[![Apex Test Coverage 25](https://img.shields.io/badge/Apex%20Test%20Coverage-25-orange.svg)]()


<!-- 
    Badges
    Salesforce badges
        Salesforce API : Version Number
        Lightning Experience : Required / Not Required (Optional, unless using LWC/Aura)
        User License: Sales / Service / Communities / Platform / None (Optional)
        Apex Code Coverage: % 100 green, >75 orange, <75 red (Required if including Apex)
-->    
> Short description. <120 characters, match the package/repo's description field.

Longform description. No title here. The quote I stole to define this from the template is - 
* "This should describe your module in broad terms, generally in just a few paragraphs; more detail of the module's routines or methods, lengthy code examples, or other in-depth material should be given in subsequent sections.
Ideally, someone who's slightly familiar with your module should be able to refresh their memory without hitting "page down". As your reader continues through the document, they should receive a progressively greater amount of knowledge." - Kirrily "Skud" Robert, perlmodstyle

## Table of Contents
<!-- Optional if doc is less than 100 lines total 
    Link to all sections, start with the next one, don't include anything above. Capture all ## headings, optional to get ### and ####, you do you.
-->
- [Repo Title _(alternative Repo Name)_](#Repo-Title-alternative-Repo-Name)
  - [Table of Contents](#Table-of-Contents)
  - [Security and Limitations (see note)](#Security-and-Limitations-see-note)
  - [Background](#Background)
  - [Install](#Install)
    - [Dependencies](#Dependencies)
  - [Usage](#Usage)
      - [method(variable1, variable2)](#methodvariable1-variable2)
  - [Extra Sections](#Extra-Sections)
    - [Security / Limitations (if not in the primary spot)](#Security--Limitations-if-not-in-the-primary-spot)
    - [Example Usage](#Example-Usage)
    - [Related Projects](#Related-Projects)
  - [Maintainers](#Maintainers)
  - [Thanks](#Thanks)
  - [Contributing](#Contributing)
  - [License](#License)

## Security and Limitations (see note)
This normally would not go here - and instead sit after Usage. If there are severe impacts or concerns to either security or system limits, you should put them upfront here, in order to immediately draw attention to them. Examples might include:
* Requiring Remote Site Settings or CSP whitelisting of apps/systems not controlled by the user nor Salesforce. Particularly if not controlled by you either.
* **Giving credentials or permissions to an external system**
* Expectation of considerable API calls (>10k) when launched, or generation of a LOT of data for some reason.
* Triggers on standard objects that don't use a best practice model of helper classes.
* Code modification of sharing rules, profiles, or roles
* Long running executions
* Setup of scheduled apex jobs

## Background

Gimmie yer life story here. Motivation, dependencies that might be unclear, what this thing is and what you're trying to accomplish. 

## Install

Illustrate how to install. If SFDX launched, should have code block(s) to illustrate scratch org creation, package installation, and any other setup steps required to get to Usage state.

### Dependencies
* AppExchange applications or other packages
* Org Shape or feature requirements
* Any other significant dependencies, Pilots, etc.

## Usage

Illustrate proper usage. If usage requires a CLI, or some form of Apex or LEX invocation (helper class or controller for pages), bring in a code block to illustrate proper usage, or ideally provide method definitions.
* Ex.
  * Apex: `Object return = mySuperCoolClass.myMethod(isThisAVariable?)`
  * LWC: `import myMethod from '@salesforce/apex/mySuperCoolClass.myMethod'` `@wire(myMethod,{isThisAVariable: 'awYeah'}) return;`

Method Definition Example 
#### method(variable1, variable2) 
**Params**
* variable1, *string*: text you want to method
* variable2, *integer*: number of times to method variable 1
**Returns**
* Type *string*

## Extra Sections
### Security / Limitations (if not in the primary spot)
### Example Usage
<!-- Are there other live uses of this project?-->
### Related Projects
<!-- Are there related projects or repos assoc with this?-->

## Maintainers
<!--Small list of folk in charge, not everyone involved.-->
[Name/Handle](https://github.com/REPOSITORYGOHEREYO)

## Thanks
<!--Don't be a jerk thank those who helped you-->
The entire main thrust/content of this doc came from - [!Richard Litt(https://github.com/RichardLitt/standard-readme/blob/master/spec.md)]'s standard-readme doc. 

## Contributing
<!--Give instructions on how to contribute to this repository. Where do I ask questions? Do you accept PRs? What are the requirements to contribute? Don't be a jerk. Use issues if you can.-->

## License
<!-- Actually required. State the owner, -->
[MIT](LICENSE)
