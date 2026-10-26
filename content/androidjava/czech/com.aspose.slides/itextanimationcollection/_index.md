---
title: ITextAnimationCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje kolekci textových animací.
type: docs
url: /cs/com.aspose.slides/itextanimationcollection/
---
**Všechny implementované rozhraní:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Reprezentuje kolekci textových animací.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek podle indexu. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Vrací všechny prvky |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Vrací prvek podle indexu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Vrací všechny prvky

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) prvek. |

**Návratová hodnota:**
com.aspose.slides.ITextAnimation[] - Pole [ITextAnimation](../../com.aspose.slides/itextanimation)