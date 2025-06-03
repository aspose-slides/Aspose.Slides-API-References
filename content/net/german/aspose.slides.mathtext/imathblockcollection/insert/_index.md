---
title: Insert
second_title: Aspose.Slides für .NET API-Referenz
description: Fügt IMathBlock an dem angegebenen Index in die Sammlung ein.
type: docs
weight: 80
url: /de/aspose.slides.mathtext/imathblockcollection/insert/
---

## IMathBlockCollection.Insert-Methode

Fügt IMathBlock an dem angegebenen Index in die Sammlung ein.

```csharp
public void Insert(int index, IMathBlock item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Der nullbasierte Index, an dem ein Element eingefügt werden soll. |
| item | IMathBlock | Das einzufügende IMathBlock. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Insert(0, block);
```

### Siehe auch

* Schnittstelle [IMathBlock](../../imathblock)
* Schnittstelle [IMathBlockCollection](../../imathblockcollection)
* Namespace [Aspose.Slides.MathText](../../imathblockcollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->