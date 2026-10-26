---
title: last_saved_time property
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/idocumentproperties/last_saved_time/
weight: 260
---
## last_saved_time Eigenschaft
Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde.
            Werte sind in UTC.P
            Schreibgeschützt im Fall von Presentation.DocumentProperties (weil es intern während des Speicherprozesses des IPresentation-Objekts aktualisiert wird). 
            Kann über die von der Methode [`IPresentationInfo.read_document_properties`](/slides/python-net/de/aspose.slides/ipresentationinfo/read_document_properties) zurückgegebene DocumentProperties-Instanz geändert werden.
            Bitte siehe das Beispiel in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** method summary.

### Definition:
```python
@property
def last_saved_time(self):
    ...

@last_saved_time.setter
def last_saved_time(self, value):
    ...
```


### Siehe auch
* Klasse [`IDocumentProperties`](/slides/python-net/de/aspose.slides/idocumentproperties)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)