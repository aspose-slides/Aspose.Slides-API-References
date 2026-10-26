---
title: MathFunction
second_title: Aspose.Slides voor Java API-referentie
description: Specificeert een functie van een argument.
type: docs
url: /nl/com.aspose.slides/mathfunction/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Specificeert een functie van een argument.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Constructoren

| Constructor | Beschrijving |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathFunction-klasse. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Initialiseert een nieuw exemplaar van de MathFunction-klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getName()](#getName--) | Functienaam Bijvoorbeeld, functienamen zijn sin en cos |
| [getBase()](#getBase--) | Functieargument |
| [getChildren()](#getChildren--) | Haalt kindelementen op |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Eigenschappen van controletekens |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Initialiseert een nieuw exemplaar van de MathFunction-klasse.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Initialiseert een nieuw exemplaar van de MathFunction-klasse.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Functienaam Bijvoorbeeld, functienamen zijn sin en cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Functieargument

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Retour:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Haalt kindelementen op

**Retour:**
com.aspose.slides.IMathElement[] - Array van [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Eigenschappen van controletekens

**Retour:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps