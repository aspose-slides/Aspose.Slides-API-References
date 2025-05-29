---
title: AlignScripts
second_title: Aspose.Slides für .NET API Referenz
description: Gibt die Ausrichtung von tiefgestellten/Hochgestellten an. Wenn true, sind tiefgestellte und hochgestellte Texte horizontal zueinander ausgerichtet. Wenn false, sind sie an die Form der Basis angeordnet. Der Standardwert ist false.
type: docs
weight: 10
url: /de/aspose.slides.mathtext/imathrightsubsuperscriptelement/alignscripts/
---

## IMathRightSubSuperscriptElement.AlignScripts-Eigenschaft

Gibt die Ausrichtung von tiefgestellten/Hochgestellten an. Wenn true, sind tiefgestellte und hochgestellte Texte horizontal zueinander ausgerichtet. Wenn false, sind sie an die Form der Basis angeordnet. Der Standardwert ist false.

```csharp
public bool AlignScripts { get; set; }
```

### Beispiele

Beispiel:

```csharp
[C#]
IMathElement baseElement = new MathematicalText("X");
IMathElement subscript = new MathematicalText("i");
IMathElement superscript = new MathematicalText("j");
MathRightSubSuperscriptElement subsuperscript = new MathRightSubSuperscriptElement(baseElement, subscript, superscript);
subsuperscript.AlignScripts = true;
```

### Siehe auch

* Schnittstelle [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement)
* Namespace [Aspose.Slides.MathText](../../imathrightsubsuperscriptelement)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->