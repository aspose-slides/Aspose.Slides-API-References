---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded egenskap
Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för denna fil är offentliga. Värdet true betyder att endast dokumentegenskaperna läses in från en krypterad presentationsfil utan att använda lösenord. Värdet false betyder att hela den krypterade presentationen läses in med rätt lösenord, inte bara dokumentegenskaperna. Om presentationen inte är krypterad är egenskapsvärdet alltid false. Om dokumentegenskaperna för en krypterad fil inte är offentliga är egenskapsvärdet alltid false. Om PresentationEx.EncryptDocumentProperties är true är värdet för IsOnlyDocumentPropertiesLoaded alltid false. Skrivskyddad **bool**.

### Definition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Se även
* klass [`IProtectionManager`](/slides/python-net/sv/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)