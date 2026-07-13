---
title: ITextAnimationCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een collectie van tekstanimaties voor.
type: docs
url: /nl/com.aspose.slides/itextanimationcollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Stelt een collectie van tekstanimaties voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert element op index. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Retourneert alle elementen |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Retourneert element op index.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Retourneert alle elementen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) element. |

**Retourwaarde:**
com.aspose.slides.ITextAnimation[] - Array van [ITextAnimation](../../com.aspose.slides/itextanimation)