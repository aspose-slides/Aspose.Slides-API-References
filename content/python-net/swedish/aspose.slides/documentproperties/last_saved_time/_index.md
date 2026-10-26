---
title: last_saved_time property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time egenskap
Returnerar datumet då en presentation senast ändrades.
            Värdena är i UTC.
            Skrivskyddad i fallet Presentation.DocumentProperties (eftersom den uppdateras internt under IPresentation-objektets sparprocess). 
            Kan ändras via DocumentProperties-instansen som returneras av metoden [`IPresentationInfo.read_document_properties`](/slides/python-net/sv/aspose.slides/ipresentationinfo/read_document_properties)
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
* klass [`DocumentProperties`](/slides/python-net/sv/aspose.slides/documentproperties)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)