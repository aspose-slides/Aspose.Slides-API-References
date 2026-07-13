---
title: ITextAnimationCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una raccolta di animazioni di testo.
type: docs
url: /it/com.aspose.slides/itextanimationcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Rappresenta una raccolta di animazioni di testo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento per indice. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Restituisce tutti gli elementi |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```

Restituisce l'elemento per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```

Restituisce tutti gli elementi

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) elemento. |

**Restituisce:**
com.aspose.slides.ITextAnimation[] - Array di [ITextAnimation](../../com.aspose.slides/itextanimation)