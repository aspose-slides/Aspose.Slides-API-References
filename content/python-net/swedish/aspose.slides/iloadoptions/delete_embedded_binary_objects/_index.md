---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects egenskap
Avgör om Aspose.Slides kommer att ta bort alla inbäddade binära objekt vid presentationens inläsning.
            
Typerna av de inbäddade binära objekten:


* VBA Project [`IPresentation.vba_project`](/slides/python-net/sv/aspose.slides/ipresentation/vba_project)
* OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/sv/aspose.slides/icontrol/active_x_control_binary)


            Läsa/skriva **bool**.


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


### Se också
* klass [`ILoadOptions`](/slides/python-net/sv/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)