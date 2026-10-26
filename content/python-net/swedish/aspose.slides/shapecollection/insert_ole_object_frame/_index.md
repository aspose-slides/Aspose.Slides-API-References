---
title: insert_ole_object_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där OLE-objektramen ska infogas. |
| x | **float** | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Skapar en ny OLE-objektram och infogar den i formsamlingen på det angivna indexet.

### Returnerar

Den nyss skapade OLE-objektramen.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Det nollbaserade indexet där OLE-objektramen ska infogas. |
| x | **float** | x-koordinaten för den nya OLE-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya OLE-ramen, i punkter. |
| width | **float** | Bredden på den nya OLE-ramen, i punkter. |
| height | **float** | Höjden på den nya OLE-ramen, i punkter. |
| class_name | **str** | Klassnamnet för OLE-objektet. |
| path | **str** | Sökvägen till den länkade filen. <br/><br/>Denna sökväg lagras oförändrad i presentationen.<br/><br/>            Om en relativ sökväg anges kommer filen vara otillgänglig när presentationen öppnas<br/><br/>            från en annan katalog. |



### Se även
* klass [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)
* klass [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe)
* klass [`ShapeCollection`](/slides/python-net/sv/aspose.slides/shapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)