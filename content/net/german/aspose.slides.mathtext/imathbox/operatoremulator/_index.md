---
title: OperatorEmulator
second_title: Aspose.Slides für .NET-API-Referenz
description: OperatorEmulator. Wenn wahr verhalten sich das Feld und sein Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet beispielsweise dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. OperatorEmulatoren werden häufig verwendet wenn eine oder mehrere Glyphen zu einem Operator kombiniert werden wie z. B.  . Standardwert false
type: docs
weight: 70
url: /de/aspose.slides.mathtext/imathbox/operatoremulator/
---
## IMathBox.OperatorEmulator property

Operator-Emulator. Wenn wahr, verhalten sich das Feld und sein Inhalt wie ein einzelner Operator und erben die Eigenschaften eines Operators. Das bedeutet beispielsweise, dass das Zeichen als Punkt für einen Zeilenumbruch dienen und an anderen Operatoren ausgerichtet werden kann. Operator-Emulatoren werden häufig verwendet, wenn eine oder mehrere Glyphen zu einem Operator kombiniert werden, wie z. B. '==' . Standardwert: false

```csharp
public bool OperatorEmulator { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathBox box = new MathematicalText("==").ToBox();
box.OperatorEmulator = true;
```

### Siehe auch

* interface [IMathBox](../../imathbox)
* namensraum [Aspose.Slides.MathText](../../imathbox)
* Montage [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->
