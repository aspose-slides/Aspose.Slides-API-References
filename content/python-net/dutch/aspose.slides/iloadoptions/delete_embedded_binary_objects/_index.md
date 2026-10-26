---
title: delete_embedded_binary_objects property
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/iloadoptions/delete_embedded_binary_objects/
weight: 60
---
## delete_embedded_binary_objects eigenschap
Bepaalt of Aspose.Slides alle ingesloten binaire objecten zal verwijderen tijdens het laden van de presentatie.
            
De typen van de ingesloten binaire objecten:


* VBA-project [`IPresentation.vba_project`](/slides/python-net/nl/aspose.slides/ipresentation/vba_project)
* OLE-object ingebedde gegevens [`IOleEmbeddedDataInfo.embedded_file_data`](/slides/python-net/nl/aspose.slides/ioleembeddeddatainfo/embedded_file_data)
* ActiveX-control binaire gegevens [`IControl.active_x_control_binary`](/slides/python-net/nl/aspose.slides/icontrol/active_x_control_binary)


Lezen/schrijven **bool**.


### Opmerkingen

Standaard is **false** .

### Definitie:
```python
@property
def delete_embedded_binary_objects(self):
    ...

@delete_embedded_binary_objects.setter
def delete_embedded_binary_objects(self, value):
    ...
```


### Zie ook
* klasse [`ILoadOptions`](/slides/python-net/nl/aspose.slides/iloadoptions)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)