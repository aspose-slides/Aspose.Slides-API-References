---
title: DeleteColumn
second_title: Aspose.Slides für .NET-API-Referenz
description: Löscht die angegebene Spalte
type: docs
weight: 120
url: /de/net/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix.DeleteColumn method

Löscht die angegebene Spalte

```csharp
public void DeleteColumn(int columnIndex)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| columnIndex | Int32 | Der nullbasierte Index der zu löschenden Spalte. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wenn Sie versuchen, die letzte einzelne Spalte in der Matrix zu löschen |
| ArgumentOutOfRangeException | Wenn columnIndex kleiner als null oder größer oder gleich ColumnCount ist |

### Beispiele

Beispiel:

```csharp
[C#]
IMathMatrix matrix = new MathMatrix(2, 3);
matrix.DeleteColumn(0);
```

### Siehe auch

* class [MathMatrix](../../mathmatrix)
* namensraum [Aspose.Slides.MathText](../../mathmatrix)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->