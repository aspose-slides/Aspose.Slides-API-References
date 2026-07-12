---
title: ITextAnimationCollection
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: A szöveganimációk gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/itextanimationcollection/
---
**Minden megvalósított interfész:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

A szöveganimációk gyűjteménye.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Az elemet index alapján adja vissza. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Az összes elemet adja vissza |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Az elemet index alapján adja vissza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int |  |

**Visszatérési érték:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Az összes elemet adja vissza

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) elem. |

**Visszatérési érték:**
com.aspose.slides.ITextAnimation[] - [ITextAnimation](../../com.aspose.slides/itextanimation) tömbje