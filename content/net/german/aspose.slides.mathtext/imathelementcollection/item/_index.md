---
title: Item
second_title: Aspose.Slides für .NET API Referenz
description: Erhält das Element am angegebenen Index. Schreibgeschütztes IMathElementaspose.slides.mathtext/imathelement.
type: docs
weight: 30
url: /de/aspose.slides.mathtext/imathelementcollection/item/
---

## IMathElementCollection-Indexer

Erhält das Element am angegebenen Index. Schreibgeschütztes [`IMathElement`](../../imathelement).

```csharp
public IMathElement this[int index] { get; }
```

| Parameter | Beschreibung |
| --- | --- |
| index | Der nullbasierte Index des abzurufenden Elements |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
IMathElement firstElem = collection[0];
```

### Siehe auch

* Schnittstelle [IMathElement](../../imathelement)
* Schnittstelle [IMathElementCollection](../../imathelementcollection)
* Namespace [Aspose.Slides.MathText](../../imathelementcollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->