---
title: AddGroupShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram kommer automatiskt att justeras för att passa alla former som läggs till i den.
type: docs
weight: 352
url: /sv/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() metod


Skapar en ny tom gruppform och lägger till den i slutet av formsamlingen. Gruppens ram kommer automatiskt att justeras för att passa alla former som läggs till i den.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Returvärde

Den nyss skapade [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) metod


Skapar en ny gruppform, konverterar den angivna SVG-bilden till individuella former och lägger till den resulterande gruppen i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Den [ISvgImage](../../isvgimage/) som innehåller vektorinnehåll för att konvertera till former. |
| x | **float** | X-koordinaten för gruppens ram, i punkter. |
| y | **float** | Y-koordinaten för gruppens ram, i punkter. |
| width | **float** | Bredden på gruppens ram, i punkter. |
| height | **float** | Höjden på gruppens ram, i punkter. |

### Returvärde

Den nyss skapade [IGroupShape](../../igroupshape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IGroupShape](../../igroupshape/)
* Klass [IShapeCollection](../)
* Klass [ISvgImage](../../isvgimage/)
* Namnrymd [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)