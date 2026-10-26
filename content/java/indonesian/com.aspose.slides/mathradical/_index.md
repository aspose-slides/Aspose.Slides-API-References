---
title: MathRadical
second_title: Referensi API Aspose.Slides untuk Java
description: Menentukan fungsi radikal yang terdiri dari basis dan derajat opsional.
type: docs
url: /id/com.aspose.slides/mathradical/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

Menentukan fungsi radikal, yang terdiri dari basis, dan derajat opsional. Contoh objek radikal adalah \\u221a\\ud835\\udc65.

--------------------

> ```
> Contoh:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Menginisialisasi instansi baru dari kelas MathRadical. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBase()](#getBase--) | Argumen basis |
| [getDegree()](#getDegree--) | Argumen derajat |
| [getHideDegree()](#getHideDegree--) | Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Properti Karakter Kontrol |
| [getChildren()](#getChildren--) | Dapatkan elemen anak |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


Menginisialisasi instansi baru dari kelas MathRadical.

--------------------

> ```
> Contoh:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Basis |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | Derajat |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argumen basis

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


Argumen derajat

--------------------

> ```
> Contoh:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**Mengembalikan:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65

--------------------

> ```
> Contoh:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Mengembalikan:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Sembunyikan derajat. Ketika true, derajat tidak ditampilkan, seperti pada \\u221a\\ud835\\udc65

--------------------

> ```
> Contoh:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Properti Karakter Kontrol

**Mengembalikan:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Dapatkan elemen anak

**Mengembalikan:**
com.aspose.slides.IMathElement[]