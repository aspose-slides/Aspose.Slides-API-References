---
title: InsertClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de la columna plantilla especificada y la inserta en la posición especificada en una tabla.
type: docs
weight: 27
url: /es/aspose.slides/icolumncollection/insertclone/
---
## IColumnCollection::InsertClone(int32_t, System::SharedPtr\<IColumn\>, bool) método

Crea una copia de la columna plantilla especificada y la inserta en la posición especificada en una tabla.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::IColumnCollection::InsertClone(int32_t index, System::SharedPtr<IColumn> templ, bool withAttachedColumns)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | Índice de una nueva columna. |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que se utiliza como plantilla. |
| withAttachedColumns | **bool** | True para copiar también todas las columnas adjuntas a la columna plantilla. |

### Valor devuelto

Columnas insertadas.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IColumn](../../icolumn/)
* Class [IColumnCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)