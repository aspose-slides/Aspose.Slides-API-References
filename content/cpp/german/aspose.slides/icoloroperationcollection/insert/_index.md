---
title: Insert()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt die neue Operation zu einer Sammlung hinzu.
type: docs
weight: 40
url: /de/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) Methode

Fügt die neue Operation zu einer Sammlung hinzu.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **int32_t** | Der Index, an dem die Operation eingefügt wird. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Operationstyp. |
| parameter | **float** | Parameter der Operation. |

### Rückgabewert

Eingefügte Operation.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) Methode

Fügt die neue Operation zu einer Sammlung hinzu.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
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
* Klasse [IColorOperation](../../icoloroperation/)
* Klasse [IColorOperationCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)