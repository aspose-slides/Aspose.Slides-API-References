---
title: IRowCollection
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Representa la colección de filas de tabla.
type: docs
url: /es/com.aspose.slides/irowcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Representa la colección de filas de tabla.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada de una tabla. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Elimina una fila en la posición especificada de una tabla. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Obtiene el elemento en el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Crea una copia de la fila de plantilla especificada y la inserta al final de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Fila que se utiliza como plantilla. |
| withAttachedRows | boolean | Verdadero para copiar también todas las filas adjuntas a la fila de plantilla. |

**Devuelve:**
com.aspose.slides.IRow[] - Filas añadidas.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Crea una copia de la fila de plantilla especificada y la inserta en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | Índice de una nueva fila. |
| templ | [IRow](../../com.aspose.slides/irow) | Fila que se utiliza como plantilla. |
| withAttachedRows | boolean | Verdadero para copiar también todas las filas adjuntas a la fila de plantilla. |

**Devuelve:**
com.aspose.slides.IRow[] - Filas insertadas.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Elimina una fila en la posición especificada de una tabla.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| firstRowIndex | int | Índice de una fila a eliminar. |
| withAttachedRows | boolean | Verdadero para eliminar también todas las filas adjuntas. |