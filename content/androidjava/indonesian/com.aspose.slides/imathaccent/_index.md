---
title: IMathAccent
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menentukan fungsi aksen yang terdiri dari dasar dan tanda diakritik gabungan Contoh ud835udc4eu0301
type: docs
url: /id/com.aspose.slides/imathaccent/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathAccent extends IMathElement
```

Menentukan fungsi aksen, yang terdiri dari dasar dan tanda diakritik gabungan Contoh: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen tempat aksen diterapkan |
| [getCharacter()](#getCharacter--) | Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302) |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argumen tempat aksen diterapkan

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  IMathElement base = accent.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
>  ```

**Mengembalikan:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |