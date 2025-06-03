---
title: SetColumnsAlignment
second_title: Referencia de API de Aspose.Slides para .NET
description: Establecer la alineación horizontal de las columnas especificadas
type: docs
weight: 200
url: /es/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---

## Método IMathMatrix.SetColumnsAlignment

Establecer la alineación horizontal de las columnas especificadas

```csharp
public void SetColumnsAlignment(int columnIndex, uint columnsCount, MathHorizontalAlignment val)
```

| Parámetro    | Tipo    | Descripción                                                       |
|--------------|---------|-------------------------------------------------------------------|
| columnIndex  | Int32   | Índice basado en cero de la primera columna para establecer alineación |
| columnsCount | UInt32  | El número de columnas para las cuales especificar la alineación   |
| val          | MathHorizontalAlignment | Nuevo valor de alineación horizontal de la columna especificada      |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.SetColumnAlignment(0, 3, MathHorizontalAlignment.Left);
```

### Véase También

* enum [MathHorizontalAlignment](../../mathhorizontalalignment)
* interface [IMathMatrix](../../imathmatrix)
* namespace [Aspose.Slides.MathText](../../imathmatrix)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->