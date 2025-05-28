---
title: EliminarFila
second_title: Referencia de API de Aspose.Slides para .NET
description: Elimina la fila especificada
type: docs
weight: 130
url: /es/aspose.slides.mathtext/mathmatrix/deleterow/
---

## Método MathMatrix.DeleteRow

Elimina la fila especificada

```csharp
public void DeleteRow(int rowIndex)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | Int32 | El índice basado en cero de la fila a eliminar. |

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Cuando intentas eliminar la última fila única en la matriz |
| ArgumentOutOfRangeException | Si rowIndex es menor que cero o mayor o igual que RowCount |

### Ejemplos

Ejemplo:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteRow(0);
```

### Véase También

* clase [MathMatrix](../../mathmatrix)
* espacio de nombres [Aspose.Slides.MathText](../../mathmatrix)
* ensamblaje [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->