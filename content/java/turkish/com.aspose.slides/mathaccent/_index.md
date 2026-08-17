---
title: MathAccent
second_title: Aspose.Slides for Java API Referansı
description: Tabandan ve birleştirici diakritik işaretten oluşan aksan işlevini belirtir. Örnek: ud835udc4eu0301
type: docs
url: /tr/com.aspose.slides/mathaccent/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Taban ve birleştirici diakritik işaretten oluşan aksan işlevini belirtir. Örnek: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Belirtilen bir matematik öğesine varsayılan aksan karakter değeriyle bir matematik aksanı oluşturur |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Belirtilen bir matematik öğesine bir matematik aksanı oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Aksanın uygulandığı argüman |
| [getCharacter()](#getCharacter--) | Accent Character Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Accent Character Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Alt öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |

### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Belirtilen bir matematik öğesine varsayılan aksan karakter değeriyle bir matematik aksanı oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak bir matematik öğesi |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Belirtilen bir matematik öğesine bir matematik aksanı oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | aksan uygulanacak matematik öğesi |
| accentCharacter | char | aksan karakteri |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Aksanın uygulandığı argüman

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```

Accent Character Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Döndürür:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```

Accent Character Değer (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps