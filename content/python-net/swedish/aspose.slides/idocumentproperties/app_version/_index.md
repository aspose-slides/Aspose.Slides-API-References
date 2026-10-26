---
title: app_version property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version egenskap
Returns the app version.
            Skrivskyddad **str**.


### Anmärkningar

The content of this element shall be in the form XX.YYYY, where X and Y represent numerical values;
            otherwise, the document shall be considered non-conformant.
            Aspose.Slides represents its version in the format XX.YYZZ, where:
            XX - major version
            YY - minor version
            ZZ - patch version
            For example, the value 23.0105 means Aspose.Slides version 23.1.5.

### Definition:
```python
@property
def app_version(self):
    ...
```


### Se även
* klass [`IDocumentProperties`](/slides/python-net/sv/aspose.slides/idocumentproperties)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)