---
title: MathAccent
second_title: Aspose.Slides para Android mediante la Referencia de la API Java
description: Especifica la función de acento que consta de una base y una marca diacrítica combinada Ejemplo ud835udc4eu0301
type: docs
url: /es/com.aspose.slides/mathaccent/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Especifica la función de acento, que consta de una base y una marca diacrítica combinada Ejemplo: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Crea un acento matemático que se aplica a un elemento matemático especificado con el valor predeterminado del carácter de acento |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Crea un acento matemático que se aplica a un elemento matemático especificado |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBase()](#getBase--) | El argumento al que se aplicó el acento |
| [getCharacter()](#getCharacter--) | Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Propiedades del carácter de control |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Crea un acento matemático que se aplica a un elemento matemático especificado con el valor predeterminado del carácter de acento

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```
**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | un elemento matemático al que aplicar el acento |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Crea un acento matemático que se aplica a un elemento matemático especificado

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el acento |
| accentCharacter | char | carácter de acento |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

El argumento al que se aplicó el acento

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```
**Devuelve:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```
**Devuelve:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```
**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | char |  |

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