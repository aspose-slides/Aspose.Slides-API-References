---
title: Traces
second_title: Référence API Aspose.Slides pour .NET
description: Obtient toutes les traces contenues dans l'élément IInk IInkTraceaspose.slides/iinktrace. Lecture seule.
type: docs
weight: 20
url: /fr/aspose.slides.ink/iink/traces/
---

## Propriété IInk.Traces

Obtient toutes les traces contenues dans l'élément IInk [`IInkTrace`](../../iinktrace). Lecture seule.

```csharp
public IInkTrace[] Traces { get; }
```

### Exemples

Exemple:

```csharp
[C#]
using (Presentation pres = new Presentation("pres.pptx"))
{
    IInk ink = (IInk)pres.Slides[0].Shapes[0];
    IInkTrace[] traces = ink.Traces;
}
```

### Voir Aussi

* interface [IInkTrace](../../iinktrace)
* interface [IInk](../../iink)
* namespace [Aspose.Slides.Ink](../../iink)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: généré par xmldocmd pour Aspose.Slides.dll -->