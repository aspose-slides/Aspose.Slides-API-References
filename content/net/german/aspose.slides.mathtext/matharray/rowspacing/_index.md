---
title: RowSpacing
second_title: Aspose.Slides für .NET-API-Referenz
description: Abstand zwischen Zeilen eines Arrays Wird nur verwendet wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte oder Multiple in diesem Fall ist die Maßeinheit Halbzeilen. Standard 0
type: docs
weight: 60
url: /de/aspose.slides.mathtext/matharray/rowspacing/
---
## MathArray.RowSpacing property

Abstand zwischen Zeilen eines Arrays Wird nur verwendet, wenn RowSpacingRule auf 3 gesetzt ist. Genau in diesem Fall ist die Maßeinheit Punkte oder Multiple, in diesem Fall ist die Maßeinheit Halbzeilen. Standard: 0

```csharp
public uint RowSpacing { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathArray mathArray = new MathArray(new MathematicalText("item1"));
mathArray.RowSpacingRule = MathRowSpacingRule.Exactly;
mathArray.RowSpacing = 10;
```

### Siehe auch

* class [MathArray](../../matharray)
* namensraum [Aspose.Slides.MathText](../../matharray)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
