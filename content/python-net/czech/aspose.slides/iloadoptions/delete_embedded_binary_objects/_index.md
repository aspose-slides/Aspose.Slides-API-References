---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects vlastnost
Určuje, zda Aspose.Slides při načítání prezentace smaže všechny vložené binární objekty.

Typy vložených binárních objektů:

* Projekt VBA [`IPresentation.vba_project`](/slides/python-net/cs/aspose.slides/ipresentation/vba_project)
* Vložená data OLE Object [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/cs/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* binární data ActiveX Control [`IControl.active_x_control_binary`](/slides/python-net/cs/aspose.slides/icontrol/active_x_control_binary)

            Čtení/Zápis **bool**.

### Poznámky

Výchozí hodnota je **false** .

### Definice:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Viz také
* třída [`ILoadOptions`](/slides/python-net/cs/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)