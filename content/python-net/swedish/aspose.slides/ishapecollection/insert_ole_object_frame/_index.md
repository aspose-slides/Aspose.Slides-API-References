---
title: insert_ole_object_frame method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Skapar en ny OLE-objektram och sätter in den i shape-samlingen på det angivna indexet.

### Returnerar
Det nyss skapade [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe).

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade index där OLE-objektramen ska infogas. |
| x | **float** | OLE-ramens x-koordinat i punkter. |
| y | **float** | OLE-ramens y-koordinat i punkter. |
| width | **float** | OLE-ramens bredd i punkter. |
| height | **float** | OLE-ramens höjd i punkter. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo) | Den inbäddade OLE-datainformationen ([`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)). |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Skapar en ny OLE-objektram och sätter in den i shape-samlingen på det angivna indexet.

### Returnerar
Det nyss skapade [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe).

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | **int** | Det nollbaserade index där OLE-objektramen ska infogas. |
| x | **float** | OLE-ramens x-koordinat i punkter. |
| y | **float** | OLE-ramens y-koordinat i punkter. |
| width | **float** | OLE-ramens bredd i punkter. |
| height | **float** | OLE-ramens höjd i punkter. |
| class_name | **str** | Klassnamnet för OLE-objektet. |
| path | **str** | Sökvägen till den länkade filen. <br/><br/>Denna sökväg lagras exakt i presentationen.<br/><br/>            Om en relativ sökväg anges, kommer filen vara oåtkomlig när presentationen öppnas<br/><br/>            från en annan katalog. |

### Se även
* klass [`IOleEmbeddedDataInfo`](/slides/python-net/sv/aspose.slides/ioleembeddeddatainfo)
* klass [`IOleObjectFrame`](/slides/python-net/sv/aspose.slides/ioleobjectframe)
* klass [`IShapeCollection`](/slides/python-net/sv/aspose.slides/ishapecollection)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)