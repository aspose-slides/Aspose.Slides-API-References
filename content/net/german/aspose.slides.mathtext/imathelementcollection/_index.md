---
title: IMathElementCollection
second_title: Aspose.Slides für .NET API-Referenz
description: Stellt eine Sammlung von mathematischen Elementen MathElement dar.
type: docs
weight: 7990
url: /de/aspose.slides.mathtext/imathelementcollection/
---

## IMathElementCollection-Schnittstelle

Stellt eine Sammlung von mathematischen Elementen (MathElement) dar.

```csharp
public interface IMathElementCollection : IEnumerable<IMathElement>
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AsIEnumerable](../../aspose.slides.mathtext/imathelementcollection/asienumerable) { get; } | Gibt die IEnumerable-Schnittstelle zurück. Nur lesbare IEnumerable. |
| [Count](../../aspose.slides.mathtext/imathelementcollection/count) { get; } | Erhält die Anzahl der tatsächlich in der Sammlung enthaltenen Elemente. Nur lesbares Int32. |
| [Item](../../aspose.slides.mathtext/imathelementcollection/item) { get; } | Erhält das Element am angegebenen Index. Nur lesbares [`IMathElement`](../imathelement). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Add](../../aspose.slides.mathtext/imathelementcollection/add)(IMathElement) | Fügt ein mathematisches Element am Ende der Sammlung hinzu. |
| [Clear](../../aspose.slides.mathtext/imathelementcollection/clear)() | Entfernt alle Elemente aus der Sammlung. |
| [Contains](../../aspose.slides.mathtext/imathelementcollection/contains)(IMathElement) | Bestimmt, ob die Sammlung einen bestimmten Wert enthält. |
| [CopyTo](../../aspose.slides.mathtext/imathelementcollection/copyto)(IMathElement[], int) | Kopiert in das angegebene Array. |
| [IndexOf](../../aspose.slides.mathtext/imathelementcollection/indexof)(IMathElement) | Bestimmt den Index eines bestimmten mathematischen Elements in der Sammlung. |
| [Insert](../../aspose.slides.mathtext/imathelementcollection/insert)(int, IMathElement) | Fügt ein mathematisches Element an der angegebenen Stelle in die Sammlung ein. |
| [Remove](../../aspose.slides.mathtext/imathelementcollection/remove)(IMathElement) | Entfernt die erste Vorkommen eines bestimmten Objekts aus der Sammlung. |
| [RemoveAt](../../aspose.slides.mathtext/imathelementcollection/removeat)(int) | Entfernt das Element am angegebenen Index der Sammlung. |

### Beispiele

Beispiel:

```csharp
[C#]
IMathElementCollection collection = new MathBlock();
```

### Siehe auch

* Schnittstelle [IMathElement](../imathelement)
* Namespace [Aspose.Slides.MathText](../../aspose.slides.mathtext)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->