---
title: MathFraction
second_title: Aspose.Slides para Android via Referência da API Java
description: Especifica o objeto fração composto por um numerador e um denominador separados por uma barra de fração.
type: docs
url: /pt/com.aspose.slides/mathfraction/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as interfaces implementadas:**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

Especifica o objeto fração, constituído por um numerador e um denominador separados por uma barra de fração. A barra de fração pode ser horizontal ou diagonal, dependendo das propriedades da fração. O objeto fração também é usado para representar a função de empilhamento, que coloca um elemento acima de outro, sem barra de fração.

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Inicializa MathFraction com o numerador, denominador e tipo especificados |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inicializa um MathFraction do tipo 'Bar' com o numerador e denominador especificados |
## Métodos

| Método | Descrição |
| --- | --- |
| [getFractionType()](#getFractionType--) | Tipo de fração Padrão: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Tipo de fração Padrão: Bar |
| [getNumerator()](#getNumerator--) | Numerador |
| [getDenominator()](#getDenominator--) | Denominador |
| [getChildren()](#getChildren--) | Obter elementos filhos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propriedades de Caracteres de Controle |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Inicializa MathFraction com o numerador, denominador e tipo especificados

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |
| fractionType | int | Tipo de fração |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


Inicializa um MathFraction do tipo 'Bar' com o numerador e denominador especificados

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerador |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominador |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


Tipo de fração Padrão: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Retorna:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


Tipo de fração Padrão: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public final IMathElement getNumerator()
```


Numerador

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Denominador

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Retorna:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obter elementos filhos

**Retorna:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propriedades de Caracteres de Controle

**Retorna:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps