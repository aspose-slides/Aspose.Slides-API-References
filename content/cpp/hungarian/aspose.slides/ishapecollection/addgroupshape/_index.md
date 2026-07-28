---
title: AddGroupShape()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehoz egy új üres csoport alakzatot, és a shape collection végére adja hozzá. A csoport kerete automatikusan igazodik a hozzáadott alakzatokhoz.
type: docs
weight: 352
url: /hu/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() módszer


Létrehoz egy új üres group\u2019s alakzatot, és a shape collection végére adja hozzá. A group\u2019s kerete automatikusan igazodik a hozzáadott alakzatokhoz.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Visszatérési érték

Az újonnan létrehozott [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) módszer


Létrehoz egy új csoport alakzatot, a megadott SVG képet egyedi alakzatokká konvertálja, és a keletkezett csoportot a shape collection végére adja hozzá.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | [ISvgImage](../../isvgimage/) tartalmazza a vektortartalmat, amelyet alakzatokká konvertálunk. |
| x | **float** | A group\u2019s x-koordinátája pontokban. |
| y | **float** | A group\u2019s y-koordinátája pontokban. |
| width | **float** | A group\u2019s keret szélessége pontokban. |
| height | **float** | A group\u2019s keret magassága pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IGroupShape](../../igroupshape/).

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IGroupShape](../../igroupshape/)
* Osztály [IShapeCollection](../)
* Osztály [ISvgImage](../../isvgimage/)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)