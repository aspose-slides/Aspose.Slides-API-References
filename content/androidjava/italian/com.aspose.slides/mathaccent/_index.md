---
title: MathAccent
second_title: Riferimento API Java per Aspose.Slides per Android
description: Specifica la funzione di accento composta da una base e da un segno diacritico combinante. Esempio ud835udc4eu0301
type: docs
url: /it/com.aspose.slides/mathaccent/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Specifica la funzione di accento, composta da una base e da un segno diacritico combinante. Esempio: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Crea un accento matematico da applicare a un elemento matematico specificato con il valore predefinito del carattere di accento |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Crea un accento matematico da applicare a un elemento matematico specificato |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | L'argomento a cui è stato applicato l'accento |
| [getCharacter()](#getCharacter--) | Carattere accento Il valore dovrebbe essere nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Carattere accento Il valore dovrebbe essere nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302) |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Crea un accento matematico da applicare a un elemento matematico specificato con il valore predefinito del carattere di accento

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | un elemento matematico a cui applicare l'accento |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Crea un accento matematico da applicare a un elemento matematico specificato

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare l'accento |
| accentCharacter | char | carattere di accento |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

L'argomento a cui è stato applicato l'accento

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Carattere accento Il valore dovrebbe essere nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Restituisce:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Carattere accento Il valore dovrebbe essere nell'intervallo (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valore predefinito: Accento circonflesso combinante (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps