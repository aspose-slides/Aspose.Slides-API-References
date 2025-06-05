---
title: DeleteColumn
second_title: Aspose.Slides para .NET API Reference
description: Elimina la columna especificada
type: docs
weight: 120
url: /es/aspose.slides.mathtext/mathmatrix/deletecolumn/
---

## MathMatrix.DeleteColumn método

Elimina la columna especificada

```csharp
public void DeleteColumn(int columnIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | Int32 | El índice basado en cero de la columna a eliminar. |

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Cuando intentas eliminar la última columna única en la matriz |
| ArgumentOutOfRangeException | Si columnIndex es menor que cero o mayor o igual a ColumnCount |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteColumn(0);
```

### Ver también

* clase [MathMatrix](../../mathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../mathmatrix)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->