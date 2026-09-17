---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides para Python vía API de .NET
description: 
type: docs
url: /es/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects propiedad
Determina si Aspose.Slides eliminará todos los objetos binarios incrustados al cargar la presentación.

Los tipos de los objetos binarios incrustados:

* VBA Project [`IPresentation.vba_project`](/slides/python-net/es/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/es/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/es/aspose.slides/icontrol/active_x_control_binary)

Lectura/escritura **bool**.

### Observaciones

El valor predeterminado es **false** .

### Definición:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Ver también
* clase [`LoadOptions`](/slides/python-net/es/aspose.slides/loadoptions)
* módulo [`aspose.slides`](/slides/python-net/es/aspose.slides)
* biblioteca [`Aspose.Slides`](/slides/python-net)