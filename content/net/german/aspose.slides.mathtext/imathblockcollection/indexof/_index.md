---
title: IndexOf
second_title: Aspose.Slides für .NET API Referenz
description: Bestimmt den Index eines bestimmten IMathBlock in der Sammlung.
type: docs
weight: 70
url: /de/aspose.slides.mathtext/imathblockcollection/indexof/
---

## IMathBlockCollection.IndexOf-Methode

Bestimmt den Index eines bestimmten IMathBlock in der Sammlung.

```csharp
public int IndexOf(IMathBlock item)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| item | IMathBlock | Das Element, das in der Sammlung gesucht werden soll. |

### Rückgabewert

Der Index von *item*, wenn es in der Sammlung gefunden wird; andernfalls -1.

### Beispiele

Beispiel:

```csharp
[C#]
IMathBlockCollection blockCollection = new MathParagraph();
IMathBlock block = new MathBlock(new MathematicalText("y"));
blockCollection.Add(block);
int index = blockCollection.IndexOf(block);
```

### Siehe auch

* Schnittstelle [IMathBlock](../../imathblock)
* Schnittstelle [IMathBlockCollection](../../imathblockcollection)
* Namespace [Aspose.Slides.MathText](../../imathblockcollection)
* Assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generiert von xmldocmd für Aspose.Slides.dll -->