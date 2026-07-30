---
title: Insert()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce la nuova operazione in una raccolta.
type: docs
weight: 79
url: /it/aspose.slides/coloroperationcollection/insert/
---
## ColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metodo

Inserisce la nuova operazione in una raccolta.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | **int32_t** | L'indice al quale l'operazione sarà inserita. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo di operazione. |
| parameter | **float** | Parametro dell'operazione. |

### Valore restituito

Operazione inserita.

## ColorOperationCollection::Insert(int32_t, ColorTransformOperation) metodo

Inserisce la nuova operazione in una raccolta.

```cpp
System::SharedPtr<IColorOperation> Aspose::Slides::ColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | **int32_t** | L'indice al quale l'operazione sarà inserita. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo di operazione. |

### Valore restituito

Operazione inserita.

## Vedi anche

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColorOperation](../../icoloroperation/)
* Class [ColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)