---
title: only_load_document_properties property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties egenskap
Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad.
            Värdet true betyder att endast dokumentegenskaper ska läsas in från en krypterad
            presentationsfil och lösenordet ska ignoreras.
            Värdet false betyder att hela den krypterade presentationen ska läsas in med rätt
            lösenord.
            Om presentationen inte är krypterad ignoreras egenskapsvärdet alltid.
            Om dokumentegenskaperna i en krypterad fil inte är offentliga och egenskapsvärdet är true
            kan dokumentegenskaperna inte läsas in och ett undantag kommer att kastas.
            Läs/skriv **bool**.

### Definition:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### Se även
* klass [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)