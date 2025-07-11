---
title: SlideSize
second_title: Aspose.Sildes für .NET API-Referenz
description: Stellt eine Größe von Folien dar.
type: docs
weight: 10190
url: /de/aspose.slides/slidesize/
---

## SlideSize-Klasse

Stellt eine Größe von Folien dar.

```csharp
public class SlideSize : DomObject<Presentation>, ISlideSize
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Orientation](../../aspose.slides/slidesize/orientation) { get; set; } | Gibt die Ausrichtung der Folie zurück oder legt sie fest. Das Ändern dieses Wertes tauscht die Dimensionen der Folie aus. Lesen/Schreiben [`SlideOrientation`](../slideorientation). |
| [Size](../../aspose.slides/slidesize/size) { get; } | Gibt die Größe in Punkten zurück. Das Zuweisen eines beliebigen Wertes setzt die [`Type`](./type)-Eigenschaft auf Custom zurück und setzt die [`Orientation`](./orientation)-Eigenschaft. Lesen/Schreiben SizeF. |
| [Type](../../aspose.slides/slidesize/type) { get; } | Gibt den Typ der Foliengröße zurück oder legt ihn fest. Das Zuweisen eines beliebigen Wertes außer Custom ändert die [`Size`](./size) entsprechend, lässt jedoch die [`Orientation`](./orientation) unverändert. Lesen/Schreiben [`SlideSizeType`](../slidesizetype). |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize)(SlideSizeType, SlideSizeScaleType) | Legt den Typ der Foliengröße fest und skaliert den Inhalt mithilfe des Skalierungstyps. Das Zuweisen eines beliebigen Wertes außer Custom ändert die [`Size`](./size) entsprechend, lässt jedoch die [`Orientation`](./orientation) unverändert. |
| [SetSize](../../aspose.slides/slidesize/setsize#setsize_1)(float, float, SlideSizeScaleType) | Legt die Größe in Punkten fest und skaliert den Inhalt mithilfe des Skalierungstyps. Das Zuweisen eines beliebigen Wertes setzt die [`Type`](./type)-Eigenschaft auf Custom zurück und setzt die [`Orientation`](./orientation)-Eigenschaft. |

### Siehe auch

* Klasse [DomObject&lt;TParent&gt;](../domobject-1)
* Klasse [Presentation](../presentation)
* Schnittstelle [ISlideSize](../islidesize)
* Namensraum [Aspose.Slides](../../aspose.slides)
* Assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->