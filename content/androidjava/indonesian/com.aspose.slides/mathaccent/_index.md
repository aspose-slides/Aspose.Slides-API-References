---
title: MathAccent
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Menentukan fungsi aksen yang terdiri dari dasar dan tanda diakritik gabungan Contoh ud835udc4eu0301
type: docs
url: /id/com.aspose.slides/mathaccent/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathAccent](../../com.aspose.slides/imathaccent), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathAccent extends MathElementBase implements IMathAccent, IHasControlCharacterProperties
```

Menentukan fungsi aksen, terdiri dari dasar dan tanda diakritik gabungan Contoh: \\ud835\\udc4e\\u0301

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathAccent(IMathElement element)](#MathAccent-com.aspose.slides.IMathElement-) | Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default |
| [MathAccent(IMathElement element, char accentCharacter)](#MathAccent-com.aspose.slides.IMathElement-char-) | Membuat aksen matematika yang diterapkan pada elemen matematika tertentu |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen tempat aksen diterapkan |
| [getCharacter()](#getCharacter--) | Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302) |
| [setCharacter(char value)](#setCharacter-char-) | Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302) |
| [getChildren()](#getChildren--) | Mendapatkan elemen anak |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
### MathAccent(IMathElement element) {#MathAccent-com.aspose.slides.IMathElement-}
```
public MathAccent(IMathElement element)
```

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu dengan nilai karakter aksen default

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |

### MathAccent(IMathElement element, char accentCharacter) {#MathAccent-com.aspose.slides.IMathElement-char-}
```
public MathAccent(IMathElement element, char accentCharacter)
```

Membuat aksen matematika yang diterapkan pada elemen matematika tertentu

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("x");
>  MathAccent accent = new MathAccent(baseElement, '~');
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan aksen |
| accentCharacter | char | karakter aksen |

### getBase() {#getBase--}
```
public final IMathElement getBase()
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
public final char getCharacter()
```

Karakter Aksen Nilai harus berada dalam rentang (U+0300\\u2013U+036F) atau (U+20D0\\u2013U+20EF) Nilai default: Combining Circumflex Accent (U+0302)

--------------------

> ```
> Example:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
>  char ch = accent.getCharacter();
> ```

**Mengembalikan:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | char |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Mendapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps