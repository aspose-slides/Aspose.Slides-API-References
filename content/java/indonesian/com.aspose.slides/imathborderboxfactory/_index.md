---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Memungkinkan membuat kotak batas matematika
type: docs
url: /id/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Memungkinkan membuat kotak batas matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Membuat kotak batas matematika dengan menerapkannya pada elemen |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Membuat kotak batas matematika dengan menerapkannya pada elemen |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
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
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
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
| strikethroughHorizontal | boolean | Garis Coret Horizontal Kotak Batas |
| strikethroughVertical | boolean | Garis Coret Vertikal Kotak Batas |
| strikethroughBottomLeftToTopRight | boolean | Garis Coret Kotak Batas Sudut Kiri Bawah ke Kanan Atas |
| strikethroughTopLeftToBottomRight | boolean | Garis Coret Kotak Batas Sudut Kiri Atas ke Kanan Bawah |

**Mengembalikan:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - elemen kotak batas baru