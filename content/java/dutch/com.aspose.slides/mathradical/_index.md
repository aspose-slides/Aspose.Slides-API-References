---
title: MathRadical
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert de radicalfunctie die bestaat uit een basis en een optionele graad.
type: docs
url: /nl/com.aspose.slides/mathradical/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Specificeert de radicalfunctie, bestaande uit een basis en een optionele graad. Een voorbeeld van een radicaal object is \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathRadical-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getBase()](#getBase--) | Basisargument |
| [getDegree()](#getDegree--) | Graadargument |
| [getHideDegree()](#getHideDegree--) | Verberg graad. Wanneer true, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Verberg graad. Wanneer true, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Eigenschappen van controlekarakters |
| [getChildren()](#getChildren--) | Haal kindelementen op |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Initialiseert een nieuw exemplaar van de MathRadical-klasse.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basis |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Graad |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Basisargument

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Graadargument

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Verberg graad. Wanneer true, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Retour:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Verberg graad. Wanneer true, wordt de graad niet weergegeven, zoals in \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Eigenschappen van controlekarakters

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haal kindelementen op

**Retour:**
com.aspose.slides.IMathElement[]