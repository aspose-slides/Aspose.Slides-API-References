---
title: InsertClone()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada en una tabla.
type: docs
weight: 66
url: /es/aspose.slides/columncollection/insertclone/
---
## ColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) método


Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada en una tabla.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de una nueva columna. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que se usa como plantilla. |
| withAttachedColumns | **bool** | True para copiar también todas las columnas adjuntas a la columna de plantilla. |

### Valor devuelto

Columnas insertadas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IColumn](../../icolumn/)
* Clase [ColumnCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)