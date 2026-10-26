---
title: MathGroupingCharacter
second_title: Referencia de la API de Aspose.Slides para Java
description: Especifica un símbolo de agrupación encima o debajo de una expresión, generalmente para resaltar la relación entre los elementos
type: docs
url: /es/com.aspose.slides/mathgroupingcharacter/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Especifica un símbolo de agrupación encima o debajo de una expresión, generalmente para resaltar la relación entre los elementos

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathGroupingCharacter con el carácter de agrupación predeterminado U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicializa una nueva instancia de la clase MathGroupingCharacter. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getCharacter()](#getCharacter--) | Grouping Character Valor predeterminado: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Valor predeterminado: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posición del carácter de agrupación. |
| [setPosition(int value)](#setPosition-int-) | Posición del carácter de agrupación. |
| [getVerticalJustification()](#getVerticalJustification--) | Justificación vertical del carácter de agrupación. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justificación vertical del carácter de agrupación. |
| [getChildren()](#getChildren--) | Obtiene los elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicializa una nueva instancia de la clase MathGroupingCharacter con el carácter de agrupación predeterminado U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la barra |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Inicializa una nueva instancia de la clase MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la barra |
| character | char | Grouping Character |
| position | int | Posición del carácter de agrupación |
| verticalJustification | int | Justificación vertical del carácter de agrupación |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumento base

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Grouping Character Valor predeterminado: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Paréntesis inferior
> ```

**Devuelve:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Grouping Character Valor predeterminado: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Paréntesis inferior
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Posición del carácter de agrupación. Predeterminado: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Devuelve:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Posición del carácter de agrupación. Predeterminado: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


Justificación vertical del carácter de agrupación. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupación está encima del objeto, VerticalJustification de Top indica que la parte superior del objeto está en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top y Top para Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Devuelve:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


Justificación vertical del carácter de agrupación. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupación está encima del objeto, VerticalJustification de Top indica que la parte superior del objeto está en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top y Top para Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtiene los elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps