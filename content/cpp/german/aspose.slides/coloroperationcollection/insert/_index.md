---
title: Insert()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt die neue Operation zu einer Sammlung hinzu.
type: docs
weight: 79
url: /de/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) Methode

Fügt die neue Operation zu einer Sammlung hinzu.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **int32_t** | Der Index, an dem die Operation eingefügt wird. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |
| parameter | **float** | Parameter der Operation. |

### Rückgabewert

Eingefügte Operation.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) Methode

Fügt die neue Operation zu einer Sammlung hinzu.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **int32_t** | Der Index, an dem die Operation eingefügt wird. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |

### Rückgabewert

Eingefügte Operation.

## Siehe auch

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)