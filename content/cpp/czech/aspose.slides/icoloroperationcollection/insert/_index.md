---
title: Insert()
second_title: Aspose.Slides pro C++ API Reference
description: Vkládá novou operaci do kolekce.
type: docs
weight: 40
url: /cs/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metoda

Vkládá novou operaci do kolekce.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **int32_t** | Index, na který bude operace vložena. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Typ operace. |
| parameter | **float** | Parametr operace. |

### Návratová hodnota

Vložená operace.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) metoda

Vkládá novou operaci do kolekce.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **int32_t** | Index, na který bude operace vložena. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Typ operace. |

### Návratová hodnota

Vložená operace.

## See Also

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)