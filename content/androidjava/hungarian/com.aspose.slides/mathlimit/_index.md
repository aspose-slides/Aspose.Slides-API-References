---
title: MathLimit
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Meghatározza a Limit objektumot, amely a vonal alatti szöveget és közvetlenül fölötte vagy alatt lévő kicsinyített méretű szöveget tartalmazza.
type: docs
url: /hu/com.aspose.slides/mathlimit/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathLimit](../../com.aspose.slides/imathlimit), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathLimit extends MathElementBase implements IMathLimit, IHasControlCharacterProperties
```

Meghatározza a Limit objektumot, amely a vonal alatti szöveget és közvetlenül fölötte vagy alatt lévő kicsinyített méretű szöveget tartalmazza.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Új példányt inicializál a MathLimit osztályból. |
| [MathLimit(IMathElement baseArg, IMathElement limit)](#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új példányt inicializál a MathLimit osztályból alsó határral |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getLimit()](#getLimit--) | Határ argumentum |
| [getUpperLimit()](#getUpperLimit--) | Megadja a felső vagy alsó határt |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | Megadja a felső vagy alsó határt |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public MathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Új példányt inicializál a MathLimit osztályból.

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"), false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |
| upperLimit | boolean |  |

### MathLimit(IMathElement baseArg, IMathElement limit) {#MathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathLimit(IMathElement baseArg, IMathElement limit)
```


Új példányt inicializál a MathLimit osztályból alsó határral

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| limit | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getLimit() {#getLimit--}
```
public final IMathElement getLimit()
```


Határ argumentum

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getUpperLimit() {#getUpperLimit--}
```
public final boolean getUpperLimit()
```


Megadja a felső vagy alsó határt

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**Visszatérési érték:**
boolean
### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public final void setUpperLimit(boolean value)
```


Megadja a felső vagy alsó határt

--------------------

> ```
> Example:
>  
>  MathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("\ud835\udc5b\u2192\u221e"));
>  limitElement.setUpperLimit(false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermek elemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps