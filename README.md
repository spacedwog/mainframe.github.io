![](https://github.com/openmainframeproject/artwork/raw/master/projects/cobol-programming-course/cobol-programming-course-color.png)

![License](https://img.shields.io/github/license/OpenMainframeProject/cobol-programming-course)

# COBOL Programming Course

This project is a set of training materials and labs for COBOL on z/OS.

## How to use

The following books are available within this repository. To get started, follow the steps in their README.
[COBOL Programming Course #1 - Getting Started]

If you run into any issues, please don't hesitate to reach out on our [slack channel](https://openmainframeproject.slack.com/archives/C011NE32Z1T).

## Discussion

You can connect with the community in a variety of ways...

- [#cobol-programming-course channel on Open Mainframe Project Slack](https://slack.openmainframeproject.org)
- ['COBOL technical questions' category on Open Mainframe Project Community Forums](https://community.openmainframeproject.org/c/cobol-technical-questions/16)
- [COBOL Programming Course Discussion Mailing list](https://lists.openmainframeproject.org/g/cobol-course-discussion)

## Providers

These materials are being used by other organizations to provide COBOL training to the community. This project, nor Open Mainframe Project, doesn't review, maintain, or endorse any one of these particular providers. If you are using these materials in your training materials, feel free [to edit and issue a pull request](https://github.com/openmainframeproject/cobol-programming-course/edit/governance-docs/README.md) to have it included.

- IBM has provided a [free environment for completing the labs](http://ibm.biz/cobollabs).
- IBM has provided a [free trial to IDz environment](https://developer.ibm.com/mainframe/products/ibm-z-open-development).

## Build

The PDF is built using the following [pandoc](https://pandoc.org/) command. Note: pdflatex is required. [MiKTeX](https://miktex.org/) can be installed to accomodate this. 

```
pandoc "COBOL Programming with VSCode.md" -o "COBOL Programming with VSCode.pdf" --number-sections --toc -B Front_Matter.tex --listings
```

`Front_Matter.tex` contains the content before the table of contents. `COBOL Programming with VSCode.md` contains the body. The command combines the two, generates the section numbers and table of contents for the body, and outputs `COBOL Programming with VSCode.pdf`

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

All contributions must align with the [Open Mainframe Project contribution guidelines](https://github.com/openmainframeproject/tac/blob/master/process/contribution_guidelines.md), including having a DCO signoff on all commits.

## Governance

This project is openly governed as defined in [GOVERNANCE.md](GOVERNANCE.md).

## Credits

The courseware materials were made available through a joint collaboration IBM, it's clients, and American River College and proposed as a new project by IBM.
