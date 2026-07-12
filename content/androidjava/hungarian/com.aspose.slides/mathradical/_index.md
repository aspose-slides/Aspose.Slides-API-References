---
title: MathRadical
second_title: Aspose.Slides Androidra vonatkozó Java API referencia
description: Meghatározza a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll.
type: docs
url: /hu/com.aspose.slides/mathradical/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Az összes megvalósított interfész:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Meghatározza a gyökfüggvényt, amely egy alapból és egy opcionális fokból áll. A gyökobjektum példája: \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Új MathRadical példányt inicializál. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getDegree()](#getDegree--) | Fok argumentum |
| [getHideDegree()](#getHideDegree--) | A fok elrejtése: Ha igaz, a fok nem jelenik meg, például \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | A fok elrejtése: Ha igaz, a fok nem jelenik meg, például \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
| [getChildren()](#getChildren--) | Gyermek elemek lekérése |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Új MathRadical példányt inicializál.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Alap |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fok |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Fok argumentum

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```


**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


A fok elrejtése: Ha igaz, a fok nem jelenik meg, például \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Visszatérési érték:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


A fok elrejtése: Ha igaz, a fok nem jelenik meg, például \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontroll karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermek elemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]