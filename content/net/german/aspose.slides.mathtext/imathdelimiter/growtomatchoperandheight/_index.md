---
title: GrowToMatchOperandHeight
second_title: Aspose.Slides für .NET-API-Referenz
description: Gibt das Wachstum von BeginningCharacter SeparatorCharacter EndingCharacter an. Wenn wahr wachsen die Trennzeichen vertikal um der Operandenhöhe zu entsprechen. Der Standardwert ist true
type: docs
weight: 60
url: /de/aspose.slides.mathtext/imathdelimiter/growtomatchoperandheight/
---
## IMathDelimiter.GrowToMatchOperandHeight property

Gibt das Wachstum von BeginningCharacter, SeparatorCharacter, EndingCharacter an. Wenn wahr, wachsen die Trennzeichen vertikal, um der Operandenhöhe zu entsprechen. Der Standardwert ist true

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

### Siehe auch

* interface [IMathDelimiter](../../imathdelimiter)
* namensraum [Aspose.Slides.MathText](../../imathdelimiter)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
