---
title: last_saved_time property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time özelliği
Returns the date a presentation was last modified.
            Values are in UTC.P
            Read-only in case of Presentation.DocumentProperties (because it will be updated internally while IPresentation object saving process). 
            Can be changed via DocumentProperties instance returning by method [`IPresentationInfo.read_document_properties`](/slides/python-net/tr/aspose.slides/ipresentationinfo/read_document_properties)
            Please see the example in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary.

### Tanım:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`IDocumentProperties`](/slides/python-net/tr/aspose.slides/idocumentproperties)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)