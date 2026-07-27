---
title: AddClone()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.
type: docs
weight: 53
url: /es/aspose.slides/columncollection/addclone/
---
## ColumnCollection::AddClone(System::SharedPtr\<IColumn\>, bool) method

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

```cpp
System::ArrayPtr<System::SharedPtr<IColumn>> Aspose::Slides::ColumnCollection::AddClone(System::SharedPtr<IColumn> templ, bool withAttachedColumns) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [System::SharedPtr](../../../system/sharedptr/)\<[IColumn](../../icolumn/)\> | [Column](../../column/) que se usa como plantilla. |
| withAttachedColumns | **bool** | Verdadero para copiar también todas las columnas adjuntas a la fila de plantilla. |

### Valor de retorno

Columnas añadidas.

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IColumn](../../icolumn/)
* Clase [ColumnCollection](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)