---
title: IMathGroupingCharacter
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Especifica un símbolo de agrupación por encima o por debajo de una expresión, normalmente para resaltar la relación entre los elementos
type: docs
url: /es/com.aspose.slides/imathgroupingcharacter/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Especifica un símbolo de agrupación por encima o por debajo de una expresión, usualmente para resaltar la relación entre elementos

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | Argumento base |
| [getCharacter()](#getCharacter--) | Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR) |
| [setCharacter(char value)](#setCharacter-char-) | Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR) |
| [getPosition()](#getPosition--) | Posición del carácter de agrupación. |
| [setPosition(int value)](#setPosition-int-) | Posición del carácter de agrupación. |
| [getVerticalJustification()](#getVerticalJustification--) | Justificación vertical del carácter de agrupación. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Justificación vertical del carácter de agrupación. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```


Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR)

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
public abstract void setCharacter(char value)
```


Carácter de agrupación Valor predeterminado: U+23DF (LLAVE CURVA INFERIOR)

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
public abstract int getPosition()
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
public abstract void setPosition(int value)
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
public abstract int getVerticalJustification()
```


Justificación vertical del carácter de agrupación. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupación está por encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se sitúa en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top, y Top para Position=Bottom

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
public abstract void setVerticalJustification(int value)
```


Justificación vertical del carácter de agrupación. Especifica la alineación del objeto con respecto a la línea base. Por ejemplo, cuando el carácter de agrupación está por encima del objeto, VerticalJustification de Top indica que la parte superior del objeto se sitúa en la línea base; cuando VerticalJustification se establece en Bottom, la parte inferior del objeto está en la línea base. Predeterminado: Bottom para Position=Top, y Top para Position=Bottom

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