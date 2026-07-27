---
title: AddClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.
type: docs
weight: 14
url: /es/aspose.slides/icolumncollection/addclone/
---
## IColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) método

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```


### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que se usa como plantilla. |
| withAttachedColumns | **bool** | True para copiar también todas las columnas adjuntas a la fila de plantilla. |

### Valor devuelto

Columnas añadidas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IColumn](../../icolumn/)
* Clase [IColumnCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)