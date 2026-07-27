---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la fila plantilla especificada y la inserta al final de una tabla.
type: docs
weight: 14
url: /es/aspose.slides/irowcollection/addclone/
---
## IRowCollection::AddClone(System::SharedPtr\<IRow\>, bool) método

Crea una copia de la fila plantilla especificada y la inserta al final de una tabla.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IRow>> Aspose::Slides::IRowCollection::AddClone(System::SharedPtr<IRow> templ, bool withAttachedRows)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IRow](../../irow/)\> | [Row](../../row/) que se usa como plantilla. |
| withAttachedRows | **bool** | True para copiar también todas las filas adjuntas a la fila plantilla. |

### Valor devuelto

Filas añadidas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IRow](../../irow/)
* Clase [IRowCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)