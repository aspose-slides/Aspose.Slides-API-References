---
title: last_saved_time property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/documentproperties/last_saved_time/
weight: 290
---
## last_saved_time Eigenschaft
Gibt das Datum zurück, an dem eine Präsentation zuletzt geändert wurde.
            Werte sind in UTC.
            Schreibgeschützt im Fall von Presentation.DocumentProperties (weil es intern während des Speichervorgangs des IPresentation-Objekts aktualisiert wird). 
            Kann über eine DocumentProperties-Instanz geändert werden, die von der Methode [`IPresentationInfo.read_document_properties`](/slides/python-net/de/aspose.slides/ipresentationinfo/read_document_properties) zurückgegeben wird.
            Bitte siehe das Beispiel in **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** Methodenzusammenfassung.

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
* Klasse [`DocumentProperties`](/slides/python-net/de/aspose.slides/documentproperties)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)