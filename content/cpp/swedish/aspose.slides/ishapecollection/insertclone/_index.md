---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 508
url: /sv/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) metod

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Den nollbaserade index där den klonade formen ska infogas. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |
| x | **float** | x-koordinaten för den klonade formens\\u2019 ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens\\u2019 ram, i punkter. |
| width | **float** | bredden för den klonade formens\\u2019 ram, i punkter. |
| height | **float** | höjden för den klonade formens\\u2019 ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) metod

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredden och höjden på *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Den nollbaserade index där den klonade formen ska infogas. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |
| x | **float** | x-koordinaten för den klonade formens\\u2019 ram, i punkter. |
| y | **float** | y-koordinaten för den klonade formens\\u2019 ram, i punkter. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) metod

Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller original\\u2019s position och storlek.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Den nollbaserade index där den klonade formen ska infogas. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | Den [IShape](../../ishape/) att klona. |

### Returvärde

Den nyss skapade [IShape](../../ishape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [IShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)