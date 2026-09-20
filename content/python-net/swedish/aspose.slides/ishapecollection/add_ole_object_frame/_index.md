---
title: add_ole_object_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Skapar en ny OLE-objektram och lägger till den i slutet av formsamlingen.

### Returnerar

Det nyss skapade [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | **float** | X-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | Y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| class_name | **str** | Klassnamnet för OLE-objektet. |
| path | **str** | Sökvägen till den länkade filen. <br/><br/>Denna sökväg lagras ordagrant i presentationen.<br/><br/>            Om en relativ sökväg anges, kommer filen vara otillgänglig när presentationen öppnas<br/><br/>            från en annan katalog. |



### Se även
* klass [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)
* klass [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)