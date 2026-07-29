---
title: AddVideoFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny video-ram och lägger till den i slutet av formsamlingen.
type: docs
weight: 209
url: /sv/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metod


Skapar en ny video-ram och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya video-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya video-ramen, i punkter. |
| width | **float** | Bredden på den nya video-ramen, i punkter. |
| height | **float** | Höjden på den nya video-ramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på videofilen som ska bäddas in. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metod


Skapar en ny video-ram och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya video-ramen, i punkter. |
| y | **float** | y-koordinaten för den nya video-ramen, i punkter. |
| width | **float** | Bredden på den nya video-ramen, i punkter. |
| height | **float** | Höjden på den nya video-ramen, i punkter. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Den [IVideo](../../ivideo/) som ska bäddas in i video-ramen. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IVideoFrame](../../ivideoframe/)
* Klass [String](../../../system/string/)
* Klass [ShapeCollection](../)
* Klass [IVideo](../../ivideo/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)