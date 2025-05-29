---
title: SetColumnAlignment
second_title: Referencia de API de Aspose.Slides para .NET
description: Establecer la alineación horizontal de la columna especificada
type: docs
weight: 200
url: /es/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---

## MathMatrix.SetColumnAlignment método

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

### Véase también

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* class [MathMatrix](../../mathmatrix)
* namespace [Aspose.Slides.MathText](../../mathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->