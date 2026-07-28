---
title: Insert()
second_title: Aspose.Slides C++ API hivatkozás
description: Beszúrja az új műveletet egy gyűjteménybe.
type: docs
weight: 79
url: /hu/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metódus

Beszúrja az új műveletet a gyűjteménybe.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | **int32_t** | Az index, amelyen a művelet be lesz szúrva. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Művelettípus. |
| parameter | **float** | A művelet paramétere. |

### Visszatérési érték

Beszúrt művelet.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) metódus

Beszúrja az új műveletet a gyűjteménybe.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| position | **int32_t** | Az index, amelyen a művelet be lesz szúrva. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Művelettípus. |

### Visszatérési érték

Beszúrt művelet.

## Lásd még

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IColorOperation](../../icoloroperation/)
* Osztály [ColorOperationCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)