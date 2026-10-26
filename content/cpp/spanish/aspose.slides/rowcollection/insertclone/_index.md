---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada en una tabla.
type: docs
weight: 66
url: /es/aspose.slides/rowcollection/insertclone/
---
## RowCollection::InsertClone(int32_t, System::SharedPtr\<IRow\>, bool) método


Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada en una tabla.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::InsertClone(int32_t index, System::SharedPtr<IRow> templ, bool withAttachedRows) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de una nueva fila. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que se utiliza como plantilla. |
| withAttachedRows | **bool** | True para copiar también todas las filas adjuntas a la fila de plantilla. |

### Valor de retorno

Filas insertadas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IRow](../../irow/)
* Clase [RowCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)