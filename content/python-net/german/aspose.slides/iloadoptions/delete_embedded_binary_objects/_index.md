---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects Eigenschaft
Bestimmt, ob Aspose.Slides beim Laden der Präsentation alle eingebetteten Binärobjekte löscht.

Die Typen der eingebetteten Binärobjekte:


* VBA Project [`IPresentation.vba_project`](/slides/python-net/de/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/de/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/de/aspose.slides/icontrol/active_x_control_binary)


            Lesen/Schreiben **bool**.

### Hinweise

Standard ist **false** .

### Definition:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Siehe auch
* Klasse [`ILoadOptions`](/slides/python-net/de/aspose.slides/iloadoptions)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)