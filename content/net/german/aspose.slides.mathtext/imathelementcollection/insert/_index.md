---
title: Insert
second_title: Aspose.Slides für .NET API-Referenz
description: Fügt ein Mathe-Element an der angegebenen Stelle in die Sammlung ein.
type: docs
weight: 90
url: /de/aspose.slides.mathtext/imathelementcollection/insert/
---

## IMathElementCollection.Insert-Methode

Fügt ein Mathe-Element an der angegebenen Stelle in die Sammlung ein.

```csharp
public void Insert(int index, IMathElement item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem das IMathElement eingefügt werden soll. |
| item | IMathElement | Das einzufügende IMathElement. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
MathematicalText plusElement = new MathematicalText("+");
collection.Add(plusElement);
collection.Insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

### Siehe auch

* Schnittstelle [IMathElement](../../imathelement)
* Schnittstelle [IMathElementCollection](../../imathelementcollection)
* Namespace [Aspose.Slides.MathText](../../imathelementcollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->