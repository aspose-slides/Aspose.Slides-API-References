---
title: ITextAnimationCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung von Textanimationen dar.
type: docs
url: /de/com.aspose.slides/itextanimationcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Stellt eine Sammlung von Textanimationen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element anhand des Index zurück. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Gibt alle Elemente zurück |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Gibt das Element anhand des Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Gibt alle Elemente zurück

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) Element. |

**Rückgabewert:**
com.aspose.slides.ITextAnimation[] - Array von [ITextAnimation](../../com.aspose.slides/itextanimation)