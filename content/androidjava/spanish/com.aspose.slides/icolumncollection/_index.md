---
title: IColumnCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de columnas en una tabla.
type: docs
url: /es/com.aspose.slides/icolumncollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Representa una colección de columnas en una tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve la columna en el índice especificado. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta en la parte inferior de una tabla. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada en una tabla. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Elimina una columna en la posición especificada de una tabla. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```

Devuelve la columna en el índice especificado. Solo lectura [IColumn](../../com.aspose.slides/icolumn).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```

Crea una copia de la fila de plantilla especificada y la inserta en la parte inferior de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Columna que se usa como plantilla. |
| withAttachedColumns | boolean | True para copiar también todas las columnas adjuntas a la fila de plantilla. |

**Devuelve:**
com.aspose.slides.IColumn[] - Columnas agregadas.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```

Crea una copia de la columna de plantilla especificada y la inserta en la posición especificada en una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una nueva columna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Columna que se usa como plantilla. |
| withAttachedColumns | boolean | True para copiar también todas las columnas adjuntas a la columna de plantilla. |

**Devuelve:**
com.aspose.slides.IColumn[] - Columnas insertadas.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```

Elimina una columna en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstColumnIndex | int | Índice de una columna a eliminar. |
| withAttachedRows | boolean | True para eliminar también todas las columnas adjuntas. |