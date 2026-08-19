---
title: ITextAnimationCollection
second_title: Aspose.Slides för Java API Referens
description: Representerar en samling textanimationer.
type: docs
url: /sv/com.aspose.slides/itextanimationcollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Representerar en samling textanimationer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar element efter index. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Returnerar alla element |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Returnerar element efter index.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Returnerar alla element

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) element. |

**Returnerar:**
com.aspose.slides.ITextAnimation[] - Array av [ITextAnimation](../../com.aspose.slides/itextanimation)