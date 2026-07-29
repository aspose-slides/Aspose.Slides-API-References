---
title: InsertVideoFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 183
url: /sv/aspose.slides/ishapecollection/insertvideoframe/
---
## IShapeCollection::InsertVideoFrame(int32_t, float, float, float, float, System::String) method

Skapar en ny video-ram och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::InsertVideoFrame(int32_t index, float x, float y, float width, float height, System::String fname)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där video-ramen ska infogas. |
| x | **float** | x-koordinaten för den nya video-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya video-ramen, i punkter. |
| width | **float** | Bredden på den nya video-ramen, i punkter. |
| height | **float** | Höjden på den nya video-ramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på videofilen som ska bäddas in. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IVideoFrame](../../ivideoframe/)
* Klass [String](../../../system/string/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)