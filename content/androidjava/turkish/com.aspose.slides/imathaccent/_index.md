---
title: IMathAccent
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir temel ve birleştirici diakritik işaretten oluşan aksan işlevini belirtir. Örnek ud835udc4eu0301
type: docs
url: /tr/com.aspose.slides/imathaccent/
---
**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Belirtilen aksan işlevi, bir temel ve bir birleştirici diakritik işaretten oluşur Örnek: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBase()](#getBase--) | Aksentin uygulandığı argüman |
| [getCharacter()](#getCharacter--) | Aksan Karakteri Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Aksan Karakteri Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302) |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Aksentin uygulandığı argüman

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
>  ```

**Döndürür:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Aksan Karakteri Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)

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
public abstract void setCharacter(char value)
```

Aksan Karakteri Değer (U+0300–U+036F) veya (U+20D0–U+20EF) aralığında olmalıdır. Varsayılan değer: Birleştirici Çatı Aksanı (U+0302)

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