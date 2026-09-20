---
title: last_saved_time property
second_title: Aspose.Slides pro Python přes .NET – reference API
description:
type: docs
url: /cs/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time vlastnost
Vrací datum, kdy byla prezentace naposledy upravena.
            Hodnoty jsou v UTC.P
            Jen pro čtení v případě Presentation.DocumentProperties (protože bude aktualizováno interně během procesu ukládání objektu IPresentation).
            Lze změnit pomocí instance DocumentProperties vrácené metodou [`IPresentationInfo.read_document_properties`](/slides/python-net/cs/aspose.slides/ipresentationinfo/read_document_properties)
            Viz příklad v **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** souhrnu metody.

### Definice:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```

### Viz také
* třída [`IDocumentProperties`](/slides/python-net/cs/aspose.slides/idocumentproperties)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)