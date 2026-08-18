---
title: MathAccent
second_title: Aspose.Slides dla Java – odniesienie API
description: Określa funkcję akcentu składającą się z podstawy i łączącego znaku diakrytycznego. Przykład ud835udc4eu0301
type: docs
url: /pl/com.aspose.slides/mathaccent/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Określa funkcję akcentu, składającą się z podstawy i łączącego znaku diakrytycznego. Example: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Tworzy akcent matematyczny stosowany do określonego elementu matematycznego |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument, do którego zastosowano akcent |
| [getCharacter()](#getCharacter--) | Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent daszka (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent daszka (U+0302) |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaków sterujących |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego z domyślną wartością znaku akcentu

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować akcent |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


Tworzy akcent matematyczny stosowany do określonego elementu matematycznego

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | element matematyczny, do którego zastosować akcent |
| accentCharacter | char | znak akcentu |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument, do którego zastosowano akcent

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent daszka (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Zwraca:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Znak akcentu Wartość powinna mieścić się w zakresie (U+0300\\u2013U+036F) lub (U+20D0\\u2013U+20EF). Domyślna wartość: Łączący akcent daszka (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaków sterujących

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps