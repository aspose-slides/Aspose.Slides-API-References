---
title: SetColumnAlignment
second_title: Referencia de la API de Aspose.Slides para .NET
description: Establecer la alineación horizontal de la columna especificada
type: docs
weight: 190
url: /es/net/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix.SetColumnAlignment method

Establecer la alineación horizontal de la columna especificada

```csharp
public void SetColumnAlignment(int columnIndex, MathHorizontalAlignment val)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| columnIndex | Int32 | Índice de columna de base cero |
| val | MathHorizontalAlignment | Nuevo valor de alineación horizontal de la columna especificada |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, MathHorizontalAlignment.Left);
```

### Ver también

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* interface [IMathMatrix](../../imathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../imathmatrix)
* asamblea [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->