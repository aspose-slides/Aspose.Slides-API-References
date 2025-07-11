---
title: OperatorEmulator
second_title: Aspose.Sildes für .NET API Referenz
description: Operator Emulator. Wenn wahr, verhält sich die Box und deren Inhalt wie ein einzelner Operator und erbt die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen kann und an anderen Operatoren ausgerichtet werden kann. Operator Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen kombiniert werden, um einen Operator wie '==' zu bilden. Standardwert false
type: docs
weight: 70
url: /de/aspose.slides.mathtext/imathbox/operatoremulator/
---

## IMathBox.OperatorEmulator Eigenschaft

Operator Emulator. Wenn wahr, verhält sich die Box und deren Inhalt wie ein einzelner Operator und erbt die Eigenschaften eines Operators. Das bedeutet zum Beispiel, dass das Zeichen als Punkt für einen Zeilenumbruch dienen kann und an anderen Operatoren ausgerichtet werden kann. Operator Emulatoren werden häufig verwendet, wenn ein oder mehrere Glyphen kombiniert werden, um einen Operator, wie '==', zu bilden. Standardwert: false

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

### Siehe Auch

* Schnittstelle [IMathBox](../../imathbox)
* Namensraum [Aspose.Slides.MathText](../../imathbox)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->