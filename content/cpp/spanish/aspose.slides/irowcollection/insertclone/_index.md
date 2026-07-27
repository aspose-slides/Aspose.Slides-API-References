---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la fila plantilla especificada y la inserta en la posición especificada de una tabla.
type: docs
weight: 27
url: /es/aspose.slides/irowcollection/insertclone/
---
## IRowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) method

Crea una copia de la fila plantilla especificada y la inserta en la posición especificada de una tabla.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de una nueva fila. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que se usa como plantilla. |
| withAttachedRows | **bool** | True para copiar también todas las filas adjuntas a la fila plantilla. |

### Valor devuelto

Filas insertadas.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [IRowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)