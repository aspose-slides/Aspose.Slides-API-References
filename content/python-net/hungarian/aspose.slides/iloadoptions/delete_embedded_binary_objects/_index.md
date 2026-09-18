---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API Referencia
description: 
type: docs
url: /hu/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects tulajdonság
Meghatározza, hogy az Aspose.Slides törli-e az összes beágyazott bináris objektumot a bemutató betöltésekor.

A beágyazott bináris objektumok típusai:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/hu/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/hu/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/hu/aspose.slides/icontrol/active_x_control_binary)

Olvasás/írás **bool**.

### Megjegyzés

Az alapértelmezett érték **false**.

### Definíció:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Lásd még
* osztály [`ILoadOptions`](/slides/python-net/hu/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)