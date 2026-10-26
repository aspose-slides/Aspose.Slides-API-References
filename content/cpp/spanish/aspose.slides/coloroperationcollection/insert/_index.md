---
title: Insert()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta la nueva operación en una colección.
type: docs
weight: 79
url: /es/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) método

Inserta la nueva operación en una colección.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| position | **int32_t** | El índice en el que se insertará la operación. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo de operación. |
| parameter | **float** | Parámetro de la operación. |

### Valor devuelto

Operación insertada.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) método

Inserta la nueva operación en una colección.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
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
* Clase [ColorOperationCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)