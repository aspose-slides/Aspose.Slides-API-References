---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded egenskap
Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för den här filen är offentliga.
Värdet true betyder att endast dokumentegenskaper laddas från en krypterad presentationsfil utan att använda lösenord.
Värdet false betyder att hela den krypterade presentationen laddas med rätt lösenord, inte bara dokumentegenskaperna laddas.
Om presentationen inte är krypterad är egenskapsvärdet alltid false.
Om dokumentegenskaperna för en krypterad fil inte är offentliga är egenskapsvärdet alltid false.
Om Presentation.EncryptDocumentProperties är true så är värdet för egenskapen IsOnlyDocumentPropertiesLoaded alltid false.
Skrivskyddad **bool**.

### Definition:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Se även
* klass [`ProtectionManager`](/slides/python-net/sv/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)