---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/loadoptions/delete_embedded_binary_objects/
weight: 70
---


## delete_embedded_binary_objects property
Determines if Aspose.Slides will delete all embedded binary objects while presentation loading.

The types of the embedded binary objects:


* 
VBA Project [`IPresentation.vba_project`](/slides/python-net/aspose.slides/ipresentation/vba_project)
* 
OLE Object embedded data [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* 
ActiveX Control binary data [`IControl.active_x_control_binary`](/slides/python-net/aspose.slides/icontrol/active_x_control_binary)


Read/write **bool**.


### Remarks

Default is **false** .

### Definition:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```


### See Also
* class [`LoadOptions`](/slides/python-net/aspose.slides/loadoptions)
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

