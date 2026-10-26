---
title: last_saved_time property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time egenskap
Returnerar datumet då en presentation senast modifierades.
            Värden är i UTC.P
            Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den kommer att uppdateras internt under sparprocessen för IPresentation-objektet). 
            Kan ändras via DocumentProperties-instans som returneras av metoden [`IPresentationInfo.read_document_properties`](/slides/python-net/sv/aspose.slides/ipresentationinfo/read_document_properties)
            Se exempel i **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** metodsammanfattning.

### Definition:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### Se även
* klass [`IDocumentProperties`](/slides/python-net/sv/aspose.slides/idocumentproperties)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)