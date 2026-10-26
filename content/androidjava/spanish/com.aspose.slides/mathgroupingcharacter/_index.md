---
title: MathGroupingCharacter
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Especifica un símbolo de agrupación arriba o debajo de una expresión, generalmente para resaltar la relación entre los elementos
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

Especifica un símbolo de agrupación arriba o debajo de una expresión, generalmente para resaltar la relación entre los elementos

--------------------

> ```
> Ejemplo:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicializa una nueva instancia de la clase MathGroupingCharacter con el carácter de agrupación predeterminado U+23DF (CORCHETE CURVO INFERIOR) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicializa una nueva instancia de la clase MathGroupingCharacter. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getCharacter()](#getCharacter--) | Carácter de agrupación Valor predeterminado: U+23DF (CORCHETE CURVO INFERIOR) |
| [setCharacter(char value)](#setCharacter-char-) | Carácter de agrupación Valor predeterminado: U+23DF (CORCHETE CURVO INFERIOR) |
| [getPosition()](#getPosition--) | Posición del carácter de agrupación. |
| [setPosition(int value)](#setPosition-int-) | Posición del carácter de agrupación. |
| [getVerticalJustification()](#getVerticalJustification--) | Justificación vertical del carácter de grupo. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justificación vertical del carácter de grupo. |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades del carácter de control |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicializa una nueva instancia de la clase MathGroupingCharacter con el carácter de agrupación predeterminado U+23DF (CORCHETE CURVO INFERIOR)

--------------------

> ```
> Ejemplo:
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
> Ejemplo:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | El elemento base al que se aplica la barra |
| character | char | Carácter de agrupación |
| position | int | Posición del carácter de agrupación |
| verticalJustification | int | Justificación vertical del carácter de grupo |

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


Carácter de agrupación Valor predeterminado: U+23DF (CORCHETE CURVO INFERIOR)

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


Carácter de agrupación Valor predeterminado: U+23DF (CORCHETE CURVO INFERIOR)

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


Posición del carácter de agrupación. Predeterminado: Inferior

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


Posición del carácter de agrupación. Predeterminado: Inferior

--------------------

> ```
> Ejemplo:
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


Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está encima del objeto, la JustificaciónVertical de Top indica que la parte superior del objeto se alinea con la línea base; cuando la JustificaciónVertical se establece en Bottom, la parte inferior del objeto está en la línea base. Valor predeterminado: Bottom para Position=Top, y Top para Position=Bottom

--------------------

> ```
> Ejemplo:
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


Justificación vertical del carácter de grupo. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de grupo está encima del objeto, la JustificaciónVertical de Top indica que la parte superior del objeto se alinea con la línea base; cuando la JustificaciónVertical se establece en Bottom, la parte inferior del objeto está en la línea base. Valor predeterminado: Bottom para Position=Top, y Top para Position=Bottom

--------------------

> ```
> Ejemplo:
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


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Propiedades del carácter de control

**Devuelve:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps