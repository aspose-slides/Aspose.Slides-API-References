---
title: AddVideoFrame()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny videoram och lägger till den i slutet av shape-samlingen.
type: docs
weight: 170
url: /sv/aspose.slides/ishapecollection/addvideoframe/
---
## IShapeCollection::AddVideoFrame(float, float, float, float, System::String) metod

Skapar en ny videoram och lägger till den i slutet av shape-samlingen.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya videoramen, i punkter. |
| y | **float** | y-koordinaten för den nya videoramen, i punkter. |
| width | **float** | Bredden på den nya videoramen, i punkter. |
| height | **float** | Höjden på den nya videoramen, i punkter. |
| fname | [System::String](../../../system/string/) | Sökvägen eller namnet på videofilen som ska bäddas in. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## IShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metod

Skapar en ny videoram och lägger till den i slutet av shape-samlingen.

```cpp
virtual System::SharedPtr<IVideoFrame> Aspose::Slides::IShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | **float** | x-koordinaten för den nya videoramen, i punkter. |
| y | **float** | y-koordinaten för den nya videoramen, i punkter. |
| width | **float** | Bredden på den nya videoramen, i punkter. |
| height | **float** | Höjden på den nya videoramen, i punkter. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Den [IVideo](../../ivideo/) som ska bäddas in i videoramen. |

### Returvärde

Den nyss skapade [IVideoFrame](../../ivideoframe/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IVideoFrame](../../ivideoframe/)
* Klass [String](../../../system/string/)
* Klass [IShapeCollection](../)
* Klass [IVideo](../../ivideo/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)