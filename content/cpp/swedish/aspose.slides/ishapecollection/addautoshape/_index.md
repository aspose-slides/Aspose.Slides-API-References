---
title: AddAutoShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny automatisk form med standardformatering och lägger till den i slutet av formsamlingen.
type: docs
weight: 313
url: /sv/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metod


Skapar en ny automatisk form med standardformatering och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Det [ShapeType](../../shapetype/) av den automatiska formen som ska läggas till. |
| x | **float** | x-koordinaten för formens ram, i punkter. |
| y | **float** | y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metod


Skapar en ny automatisk form och lägger till den i slutet av formsamlingen, eventuellt initierar den med standardmallformatering.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Det [ShapeType](../../shapetype/) av den automatiska formen som ska läggas till. |
| x | **float** | x-koordinaten för formens ram, i punkter. |
| y | **float** | y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |
| createFromTemplate | **bool** | Sant för att tillämpa standardmallstilar (enkel stil, centrerad text och icke-tomt namn) på den nya formen; falskt för att skapa formen med alla egenskaper satta till sina standardvärden. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)