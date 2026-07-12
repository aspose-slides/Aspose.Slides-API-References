---
title: MathFraction
second_title: Aspose.Slides para Android vía referencia de la API Java
description: Especifica el objeto fracción que consta de un numerador y un denominador separados por una barra de fracción.
type: docs
url: /es/com.aspose.slides/mathfraction/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las Interfaces Implementadas:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Especifica el objeto fracción, que consiste en un numerador y un denominador separados por una barra de fracción. La barra de fracción puede ser horizontal o diagonal, según las propiedades de la fracción. El objeto fracción también se usa para representar la función de apilamiento, que coloca un elemento sobre otro, sin barra de fracción.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Inicializa MathFraction con el numerador, denominador y tipo especificados |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa un MathFraction de tipo 'Bar' con el numerador y denominador especificados |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo de fracción Predeterminado: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo de fracción Predeterminado: Bar |
| [getNumerator()](#getNumerator--) | Numerador |
| [getDenominator()](#getDenominator--) | Denominador |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades de Carácter de Control |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Inicializa MathFraction con el numerador, denominador y tipo especificados

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fracción |
### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Inicializa un MathFraction de tipo 'Bar' con el numerador y denominador especificados

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Tipo de fracción Predeterminado: Bar

--------------------

> ```
> Ejemplo:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Devuelve:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Tipo de fracción Predeterminado: Bar

--------------------

> ```
> Ejemplo:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Numerador

--------------------

> ```
> Ejemplo:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Denominador

--------------------

> ```
> Ejemplo:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propiedades de Carácter de Control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps