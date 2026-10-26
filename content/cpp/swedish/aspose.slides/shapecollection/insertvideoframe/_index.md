---
title: InsertVideoFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny videoram och infogar den i ShapeCollection på det angivna indexet.
type: docs
weight: 222
url: /sv/aspose.slides/shapecollection/insertvideoframe/
---
## ShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) metod


Skapar en ny videoram och infogar den i ShapeCollection på det angivna indexet.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där videoramen ska infogas. |
| x | **float** | x-koordinaten för den nya videoramen, i punkter. |
| y | **float** | y-koordinaten för den nya videoramen, i punkter. |
| width | **float** | Bredden på den nya videoramen, i punkter. |
| height | **float** | Höjden på den nya videoramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på videofilen som ska bäddas in. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IVideoFrame](../../ivideoframe/)
* Klass [String](../../../system/string/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)