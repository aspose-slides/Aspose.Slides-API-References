---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---
## delete_embedded_binary_objects egenskap
Bestämmer om Aspose.Slides ska radera alla inbäddade binära objekt vid inläsning av presentationen.

Typerna av de inbäddade binära objekten:

* VBA-projekt [`IPresentation.vba_project`](/slides/python-net/sv/aspose.slides/ipresentation/vba_project)
* OLE-objekt inbäddad data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX-kontroll binär data [`IControl.active_x_control_binary`](/slides/python-net/sv/aspose.slides/icontrol/active_x_control_binary)

Läs/skriv **bool**.

### Anmärkningar

Standard är **false** .

### Definition:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```

### Se även
* klass [`LoadOptions`](/slides/python-net/sv/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)