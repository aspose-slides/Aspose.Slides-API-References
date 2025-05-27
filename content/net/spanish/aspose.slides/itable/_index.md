---
title: ITable
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una tabla en una diapositiva.
type: docs
weight: 7010
url: /es/aspose.slides/itable/
---

## Interfaz ITable

Representa una tabla en una diapositiva.

```csharp
public interface ITable : IBulkTextFormattable, IGraphicalObject
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIBulkTextFormattable](../../aspose.slides/itable/asibulktextformattable) { get; } | Permite obtener la interfaz base IBulkTextFormattable. Solo lectura [`IBulkTextFormattable`](../ibulktextformattable). |
| [AsIGraphicalObject](../../aspose.slides/itable/asigraphicalobject) { get; } | Permite obtener la interfaz base IGraphicalObject. Solo lectura [`IGraphicalObject`](../igraphicalobject). |
| [Columns](../../aspose.slides/itable/columns) { get; } | Devuelve la colección de columnas. Solo lectura [`IColumnCollection`](../icolumncollection). |
| [FirstCol](../../aspose.slides/itable/firstcol) { get; set; } | Determina si la primera columna de una tabla debe dibujarse con un formato especial. Lectura/escritura Boolean. |
| [FirstRow](../../aspose.slides/itable/firstrow) { get; set; } | Determina si la primera fila de una tabla debe dibujarse con un formato especial. Lectura/escritura Boolean. |
| [HorizontalBanding](../../aspose.slides/itable/horizontalbanding) { get; set; } | Determina si las filas pares deben dibujarse con un formato diferente. Lectura/escritura Boolean. |
| [Item](../../aspose.slides/itable/item) { get; } | Devuelve la celda en los índices de columna y fila especificados. Solo lectura [`ICell`](../icell). |
| [LastCol](../../aspose.slides/itable/lastcol) { get; set; } | Determina si la última columna de una tabla debe dibujarse con un formato especial. Lectura/escritura Boolean. |
| [LastRow](../../aspose.slides/itable/lastrow) { get; set; } | Determina si la última fila de una tabla debe dibujarse con un formato especial. Lectura/escritura Boolean. |
| [RightToLeft](../../aspose.slides/itable/righttoleft) { get; set; } | Determina si la tabla tiene un orden de lectura de derecha a izquierda. Lectura/escritura Boolean. |
| [Rows](../../aspose.slides/itable/rows) { get; } | Devuelve la colección de filas. Solo lectura [`IRowCollection`](../irowcollection). |
| [StylePreset](../../aspose.slides/itable/stylepreset) { get; set; } | Obtiene o establece el estilo de tabla incorporado. Lectura/escritura [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/itable/tableformat) { get; } | Devuelve el objeto TableFormat que contiene propiedades de formato para esta tabla. Solo lectura [`ITableFormat`](../itableformat). |
| [VerticalBanding](../../aspose.slides/itable/verticalbanding) { get; set; } | Determina si las columnas pares deben dibujarse con un formato diferente. Lectura/escritura Boolean. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [MergeCells](../../aspose.slides/itable/mergecells)(ICell, ICell, bool) | Fusiona celdas vecinas. |

### Véase también

* interfaz [IBulkTextFormattable](../ibulktextformattable)
* interfaz [IGraphicalObject](../igraphicalobject)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->