---
title: GrowToMatchOperandHeight
second_title: Aspose.Slides für .NET API-Referenz
description: Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn wahr, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzugleichen. Der Standardwert ist wahr.
type: docs
weight: 60
url: /de/aspose.slides.mathtext/mathdelimiter/growtomatchoperandheight/
---

## MathDelimiter.GrowToMatchOperandHeight-Eigenschaft

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter und EndingCharacter an. Wenn wahr, wachsen die Trennzeichen vertikal, um die Höhe ihres Operanden anzugleichen. Der Standardwert ist wahr.

```csharp
public bool GrowToMatchOperandHeight { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathDelimiter delimiter = new MathematicalText("x").Divide("y").Enclose();
delimiter.GrowToMatchOperandHeight = false;
```

### Siehe Auch

* Klasse [MathDelimiter](../../mathdelimiter)
* Namespace [Aspose.Slides.MathText](../../mathdelimiter)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->