---
title: AddVideoFrame()
second_title: Aspose.Slides C++ API-referencia
description: Új videokeretet hoz létre, és a shape-gyűjtemény végéhez adja hozzá.
type: docs
weight: 209
url: /hu/aspose.slides/shapecollection/addvideoframe/
---
## ShapeCollection::AddVideoFrame(float, float, float, float, System::String) metódus


Új videokeretet hoz létre, és a shape-gyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::String fname) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új videokeret x-koordinátája pontban. |
| y | **float** | Az új videokeret y-koordinátája pontban. |
| width | **float** | Az új videokeret szélessége pontban. |
| height | **float** | Az új videokeret magassága pontban. |
| fname | [System::String](../../../system/string/) | A beágyazandó videofájl elérési útja vagy neve. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## ShapeCollection::AddVideoFrame(float, float, float, float, System::SharedPtr\<IVideo\>) metódus


Új videokeretet hoz létre, és a shape-gyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<IVideoFrame> Aspose::Slides::ShapeCollection::AddVideoFrame(float x, float y, float width, float height, System::SharedPtr<IVideo> video) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| x | **float** | Az új videokeret x-koordinátája pontban. |
| y | **float** | Az új videokeret y-koordinátája pontban. |
| width | **float** | Az új videokeret szélessége pontban. |
| height | **float** | Az új videokeret magassága pontban. |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | A [IVideo](../../ivideo/) a videokeretbe ágyazandó. |

### Visszatérési érték

Az újonnan létrehozott [IVideoFrame](../../ivideoframe/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IVideoFrame](../../ivideoframe/)
* Osztály [String](../../../system/string/)
* Osztály [ShapeCollection](../)
* Osztály [IVideo](../../ivideo/)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)