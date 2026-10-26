---
title: ITextAnimationCollection
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa una colección de animaciones de texto.
type: docs
url: /es/com.aspose.slides/itextanimationcollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface ITextAnimationCollection extends IGenericCollection<ITextAnimation>
```

Representa una colección de animaciones de texto.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Devuelve el elemento por índice. |
| [get_Item(IShape shape)](#get-Item-com.aspose.slides.IShape-) | Devuelve todos los elementos |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITextAnimation get_Item(int index)
```


Devuelve el elemento por índice.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### get_Item(IShape shape) {#get-Item-com.aspose.slides.IShape-}
```
public abstract ITextAnimation[] get_Item(IShape shape)
```


Devuelve todos los elementos

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) elemento. |

**Devuelve:**
com.aspose.slides.ITextAnimation[] - Matriz de [ITextAnimation](../../com.aspose.slides/itextanimation)