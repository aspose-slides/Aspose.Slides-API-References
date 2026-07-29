---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.
type: docs
weight: 560
url: /sv/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) method


Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |
| width | **float** | The width of the cloned shape\\u2019s frame, in points. |
| height | **float** | The height of the cloned shape\\u2019s frame, in points. |

### Returvärde

Det nyss skapade [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) method


Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den nya formen behåller bredden och höjden på *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |
| x | **float** | The x-coordinate of the cloned shape\\u2019s frame, in points. |
| y | **float** | The y-coordinate of the cloned shape\\u2019s frame, in points. |

### Returvärde

Det nyss skapade [IShape](../../ishape/).

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) method


Skapar en kopia av den angivna formen och infogar den i formsamlingen på det angivna indexet. Den klonade formen behåller originalets position och storlek.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index at which to insert the cloned shape. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | The [IShape](../../ishape/) to clone. |

### Returvärde

Det nyss skapade [IShape](../../ishape/).

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../ishape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)