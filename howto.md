---
layout: howto
title: How To
permalink: /howto/
---
# How to add a new tool

## Requirements

To add a new tool, you need to have a GitHub account. If you don't have one, you can create one [here](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E%2F%3Crepo-name%3E%2Fcompare%2Fshow&source=header-repo&source_repo=seung-lab%2Fflywire-marketplace).

## Instructions
1. Fork the repository
2. Create a new file in the [`_tools` folder](https://github.com/seung-lab/flywire-marketplace/tree/master/_tools) 
    * The file name should be the name of the tool, all lowercase, with dashes instead of spaces, and with the `.md` extension. For example, if the tool is called "Navis", the file name should be `navis.md`.
3. Copy the following snippet into the file and fill in the details
4. Fill in the details, replacing the text in the brackets with your own
5. Save the file, and commit the changes
6. Pull request the changes to the main repository
7. After the submission is reviewed and merged, the tool will appear on the website


## Template

```yaml
---
layout: tools
title: {tool_name}
subtitle: {short description}
source: {Link to the tool}
image: {url of representative image}
category: {python, R, matlab, javascript, other}
tags:
  - {tags/languages/keywords}
---
{Description of the tool}
```