---
title: MathBorderBoxFactory
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mengizinkan pembuatan kotak batas matematika
type: docs
url: /id/com.aspose.slides/mathborderboxfactory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Mengizinkan pembuatan kotak batas matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Membuat kotak batas matematika dengan menerapkannya pada elemen |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Membuat kotak batas matematika dengan menerapkannya pada elemen |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Membuat kotak batas matematika dengan menerapkannya pada elemen

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan kotak batas |

**Mengembalikan:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - elemen kotak batas baru
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Membuat kotak batas matematika dengan menerapkannya pada elemen

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan kotak batas |
| hideTop | boolean | Sembunyikan Tepi Atas |
| hideBottom | boolean | Sembunyikan Tepi Bawah |
| hideLeft | boolean | Sembunyikan Tepi Kiri |
| hideRight | boolean | Sembunyikan Tepi Kanan |
| strikethroughHorizontal | boolean | Garis Coret Kotak Batas Horizontal |
| strikethroughVertical | boolean | Garis Coret Kotak Batas Vertikal |
| strikethroughBottomLeftToTopRight | boolean | Garis Coret Kotak Batas Kiri-Bawah ke Kanan-Atas |
| strikethroughTopLeftToBottomRight | boolean | Garis Coret Kotak Batas Kiri-Atas ke Kanan-Bawah |

**Mengembalikan:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - elemen kotak batas baru