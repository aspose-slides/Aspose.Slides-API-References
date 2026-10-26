---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.
type: docs
weight: 53
url: /es/aspose.slides/rowcollection/addclone/
---
## RowCollection::AddClone(System::SharedPtr\<IRow\>, bool) método

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

```cpp
System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::RowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que se usa como plantilla. |
| withAttachedRows | **bool** | True para copiar también todas las filas adjuntas a la fila de plantilla. |

### Valor devuelto

Filas añadidas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IRow](../../irow/)
* Class [RowCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)