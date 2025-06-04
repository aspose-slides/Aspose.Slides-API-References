---
title: SetColumnAlignment
second_title: Aspose.Slides para .NET Referencia de API
description: Establecer la alineación horizontal de la columna especificada
type: docs
weight: 190
url: /es/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---

## IMathMatrix.SetColumnAlignment método

Establecer la alineación horizontal de la columna especificada

```csharp
public void SetColumnAlignment(int columnIndex, MathHorizontalAlignment val)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | Int32 | Índice de columna basado en cero |
| val | MathHorizontalAlignment | Nuevo valor de alineación horizontal de la columna especificada |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, MathHorizontalAlignment.Left);
```

### Ver También

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* interface [IMathMatrix](../../imathmatrix)
* namespace [Aspose.Slides.MathText](../../imathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->