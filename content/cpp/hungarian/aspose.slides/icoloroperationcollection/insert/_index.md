---
title: Insert()
second_title: Aspose.Slides for C++ API-referencia
description: Beszúrja az új műveletet egy gyűjteménybe.
type: docs
weight: 40
url: /hu/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metódus


Beszúrja az új műveletet egy gyűjteménybe.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | **int32_t** | The index at which the operation will be inserted. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Művelet típusa. |
| parameter | **float** | A művelet paramétere. |

### Visszatérési érték

Beszúrt művelet.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) metódus


Beszúrja az új műveletet egy gyűjteménybe.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | **int32_t** | The index at which the operation will be inserted. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Művelet típusa. |

### Visszatérési érték

Beszúrt művelet.

## Lásd még

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColorOperation](../../icoloroperation/)
* Osztály [IColorOperationCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)