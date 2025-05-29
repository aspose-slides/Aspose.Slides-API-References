---
title: GetEffective
second_title: Referencia de API de Aspose.Slides para .NET
description: Obtiene las propiedades de formato de columna de tabla efectivas con herencia y estilos de tabla aplicados.
type: docs
weight: 10
url: /es/aspose.slides/columnformat/geteffective/
---

## Método ColumnFormat.GetEffective

Obtiene las propiedades de formato de columna de tabla efectivas con herencia y estilos de tabla aplicados.

```csharp
public IColumnFormatEffectiveData GetEffective()
```

### Valor de retorno

Un [`IColumnFormatEffectiveData`](../../icolumnformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla. Tenga en cuenta que el formato de celda siempre tiene una prioridad más alta que el formato de fila, el formato de fila - más alto que el de columna, y el formato de columna - más alto que la tabla completa. Por lo tanto, finalmente las propiedades de CellFormatEffectiveData siempre se utilizan para dibujar la tabla. El siguiente código es solo un ejemplo de API.

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

### Véase también

* interface [IColumnFormatEffectiveData](../../icolumnformateffectivedata)
* class [ColumnFormat](../../columnformat)
* namespace [Aspose.Slides](../../columnformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->