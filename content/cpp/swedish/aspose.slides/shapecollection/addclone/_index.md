---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.
type: docs
weight: 547
url: /sv/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Formen att klona. |
| x | **float** | x-koordinaten för den nya formens ram, i punkter. |
| y | **float** | y-koordinaten för den nya formens ram, i punkter. |
| width | **float** | Bredden på den nya formens ram, i punkter. |
| height | **float** | Höjden på den nya formens ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float) method

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den nya formen behåller bredden och höjden på *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Formen att klona. |
| x | **float** | x-koordinaten för den nya formens ram, i punkter. |
| y | **float** | y-koordinaten för den nya formens ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Skapar en kopia av den angivna formen och lägger till den i slutet av formsamlingen. Den klonade formen behåller original\\u2019s position och storlek.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)