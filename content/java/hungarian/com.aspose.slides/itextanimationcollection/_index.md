---
title: ITextAnimationCollection
second_title: Aspose.Slides Java API Referencia
description: A szöveganimációk gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/itextanimationcollection/
---
**Az összes megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Szöveganimációk gyűjteményét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Visszatér az elemmel index szerint. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Visszatér az összes elemmel |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Visszatér az elemmel index szerint.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatér:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Visszatér az összes elemmel

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) elem. |

**Visszatér:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) tömbje