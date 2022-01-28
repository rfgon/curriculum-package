# Curriculum Vitae Template LaTeX Package

## Table of Contents

* [Introduction](#introduction)
* [Requirements](#requirements)
* [Usage](#usage)
* [Technologies](#technologies)
* [License](#license)

## Introduction

This package provides simple commands to easily create a CV.

## Requirements

- [TeX Live](https://www.tug.org/texlive/) 2020.20210202-3

## Usage

1. Put the *curriculum.sty* package inside the same folder as your *.tex* file.
2. Include `\usepackage{curriculum}` in the preamble.

### Commands

The following list contains a description of all the commands:

- `\Candidate{`*Person's name*`}`
- `\CurrentTitle{`*Person's title*`}`
- `\Email{`*Email*`}`
- `\Phone{`*Phone number*`}`
- `\Linkedin{`*LinkedIn username*`}`
- `\Github{`*GitHub username*`}`
- `\AboutMe{`*Personal description*`}`
- `\ExperienceMilestone{`*Work title*`}{`*Date*`}{`*Location*`}{`*Work hours*`}{`*Important project*`}`
    - Every command call adds another entry to the list.
- `\EducationMilestone{`*Degree*`}{`*Date*`}{`*Location*`}{`*Thesis' title*`}{`*Main subjects*`}`
    - Every command call adds another entry to the list.
- `\Certificate{`*Title*`}{`*Date*`}{`*Location*`}`
    - Every command call adds another entry to the list.
- `\ProjectActivity{`*Date*`}{`*Location*`}{`*Description*`}`
    - Every command call adds another entry to the list.
- `\LeftSideWidth{`*Percentage of \textwidth*`}`
- `\Language{`*Language*`}{`*Proficiency*`}`
    - Every command call adds another entry to the list.
- `\Skill{`*Hard skill*`}`
    - Every command call adds another entry to the list.
- `\SoftSkill{`*Highlighted portion of soft skill*`}{`*Nonhighlighted portion of soft skill*`}`
    - Every command call adds another entry to the list.
- `\Interest{`*Highlighted portion of personal interest*`}{`*Nonhighlighted portion of personal interest*`}`
    - Every command call adds another entry to the list.
- `\MakeCurriculum`
    - Must be the last command used, which will generate the CV.

## Technologies

This project was created with:
- LaTeX

## License

This project is licensed under the [MIT License](LICENSE).  
&copy; 2022 [Rodrigo Gonçalves](https://github.com/rfgon)

[Back to top](#curriculum-vitae-template-latex-package)
