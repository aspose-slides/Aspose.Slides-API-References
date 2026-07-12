---
title: MathAccent
second_title: Aspose.Slides for Android Java API Referansı
description: Bir temel ve bir birleşik diakritik işaretten oluşan vurgu işlevini belirtir. Örnek ud835udc4eu0301
type: docs
url: /tr/com.aspose.slides/mathaccent/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Bir temel ve bir birleşik diakritik işaretten oluşan vurgu işlevini belirtir. Örnek: \\ud835\\udc4e\\u0301

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
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Belirtilen bir matematik öğesine varsayılan vurgu karakteri değeriyle bir matematik vurgu oluşturur |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Belirtilen bir matematik öğesine bir matematik vurgu oluşturur |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Vurgunun uygulandığı argüman |
| [getCharacter()](#getCharacter--) | Vurgu Karakteri Değer, (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleşik Çatı Vurgu (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Vurgu Karakteri Değer, (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleşik Çatı Vurgu (U+0302) |
| [getChildren()](#getChildren--) | Çocuk öğeleri al |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontrol Karakteri Özellikleri |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```


Belirtilen bir matematik öğesine varsayılan vurgu karakteri değeriyle bir matematik vurgu oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | vurgu uygulamak için bir matematik öğesi |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```


Belirtilen bir matematik öğesine bir matematik vurgu oluşturur

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```


**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | vurgu uygulamak için matematik öğesi |
| accentCharacter | char | accent character |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Vurgunun uygulandığı argüman

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


Vurgu Karakteri Değer, (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleşik Çatı Vurgu (U+0302)

--------------------

> ```
> Örnek:
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


Vurgu Karakteri Değer, (U+0300\\u2013U+036F) veya (U+20D0\\u2013U+20EF) aralığında olmalıdır. Varsayılan değer: Birleşik Çatı Vurgu (U+0302)

--------------------

> ```
> Örnek:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parametreler:**
| Parameter | Type | Açıklama |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Çocuk öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontrol Karakteri Özellikleri

**Döndürür:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps