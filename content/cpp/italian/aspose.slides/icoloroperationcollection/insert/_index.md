---
title: Insert()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce la nuova operazione in una collezione.
type: docs
weight: 40
url: /it/aspose.slides/icoloroperationcollection/insert/
---
## IColorOperationCollection::Insert(int32_t, ColorTransformOperation, float) metodo

Inserisce la nuova operazione in una collezione.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation, float parameter)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | **int32_t** | L’indice al quale l'operazione verrà inserita. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo di operazione. |
| parameter | **float** | Parametro dell'operazione. |

### Valore di ritorno

Operazione inserita.

## IColorOperationCollection::Insert(int32_t, ColorTransformOperation) metodo

Inserisce la nuova operazione in una collezione.

```cpp
virtual System::SharedPtr<IColorOperation> Aspose::Slides::IColorOperationCollection::Insert(int32_t position, ColorTransformOperation operation)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | **int32_t** | L’indice al quale l'operazione verrà inserita. |
| operation | [ColorTransformOperation](../../colortransformoperation/) | Tipo di operazione. |

### Valore di ritorno

Operazione inserita.

## Vedi anche

* Enum [ColorTransformOperation](../../colortransformoperation/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IColorOperation](../../icoloroperation/)
* Classe [IColorOperationCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)