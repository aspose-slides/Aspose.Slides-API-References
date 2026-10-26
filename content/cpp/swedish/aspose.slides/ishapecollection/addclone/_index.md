---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
type: docs
weight: 495
url: /sv/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) metod

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Formen att klona. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |
| width | **float** | Bredden på den klonade formens ram, i punkter. |
| height | **float** | Höjden på den klonade formens ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) metod

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredden och höjden på *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |
| x | **float** | x-koordinaten för den klonade formens ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) metod

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller originalets position och storlek.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)