---
title: Insert()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta la nueva operación en una colección.
type: docs
weight: 40
url: /es/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) método

Inserta la nueva operación en una colección.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | **int32_t** | El índice en el que se insertará la operación. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo de operación. |
| parameter | **float** | Parámetro de la operación. |

### Valor devuelto

Operación insertada.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) método

Inserta la nueva operación en una colección.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | **int32_t** | El índice en el que se insertará la operación. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo de operación. |

### Valor devuelto

Operación insertada.

## Ver también

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IColorOperation](../../icoloroperation/)
* Clase [IColorOperationCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)