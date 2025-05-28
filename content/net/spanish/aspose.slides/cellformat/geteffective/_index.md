---
title: GetEffective
second_title: Aspose.Slides para .NET Referencia de API
description: Obtiene propiedades de formato de celda de tabla efectivas con herencia y estilos de tabla aplicados.
type: docs
weight: 90
url: /es/aspose.slides/cellformat/geteffective/
---

## Método CellFormat.GetEffective

Obtiene propiedades de formato de celda de tabla efectivas con herencia y estilos de tabla aplicados.

```csharp
public ICellFormatEffectiveData GetEffective()
```

### Valor de Retorno

Un [`ICellFormatEffectiveData`](../../icellformateffectivedata).

### Ejemplos

Este ejemplo demuestra cómo obtener el formato de relleno efectivo para diferentes partes lógicas de la tabla. Tenga en cuenta que el formato de celda siempre tiene una prioridad más alta que el formato de fila, el formato de fila - más alto que el de columna, el formato de columna - más alto que la tabla completa. Así que, al final, las propiedades de CellFormatEffectiveData se utilizan siempre para dibujar la tabla. El siguiente código es solo un ejemplo de la API.

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

* interfaz [ICellFormatEffectiveData](../../icellformateffectivedata)
* clase [CellFormat](../../cellformat)
* espacio de nombres [Aspose.Slides](../../cellformat)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->