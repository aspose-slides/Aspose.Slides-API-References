---
title: GetEffective
second_title: Referencia de la API de Aspose.Slides para .NET
description: Obtiene propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados.
type: docs
weight: 10
url: /es/aspose.slides/rowformat/geteffective/
---

## Método RowFormat.GetEffective

Obtiene propiedades de formato de fila de tabla efectivas con herencia y estilos de tabla aplicados.

```csharp
public IRowFormatEffectiveData GetEffective()
```

### Valor de Retorno

Un [`IRowFormatEffectiveData`](../../irowformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla. Tenga en cuenta que el formato de celda siempre tiene mayor prioridad que el formato de fila, el formato de fila - mayor que el de columna, el de columna - mayor que el de toda la tabla. Por lo tanto, las propiedades de CellFormatEffectiveData siempre se utilizan para dibujar la tabla. El siguiente código es solo un ejemplo de la API.

```csharp
[C#]
using (Presentation pres = new Presentation(@"MyPresentation.pptx"))
{
    ITable tbl = pres.Slides[0].Shapes[0] as ITable;
    IFillFormatEffectiveData tableFillFormatEffective = tbl.TableFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData rowFillFormatEffective = tbl.Rows[0].RowFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData columnFillFormatEffective = tbl.Columns[0].ColumnFormat.GetEffective().FillFormat;
    IFillFormatEffectiveData cellFillFormatEffective = tbl[0, 0].CellFormat.GetEffective().FillFormat;
    /* Salida y comparación */
}
```

### Véase También

* interfaz [IRowFormatEffectiveData](../../irowformateffectivedata)
* clase [RowFormat](../../rowformat)
* espacio de nombres [Aspose.Slides](../../rowformat)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->