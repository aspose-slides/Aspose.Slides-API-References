---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
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

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan kotak batas |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - elemen kotak batas baru
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Membuat kotak batas matematika dengan menerapkannya pada elemen

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemen matematika untuk menerapkan kotak batas |
| hideTop | boolean | Sembunyikan tepi atas |
| hideBottom | boolean | Sembunyikan tepi bawah |
| hideLeft | boolean | Sembunyikan tepi kiri |
| hideRight | boolean | Sembunyikan tepi kanan |
| strikethroughHorizontal | boolean | Garis coret horizontal pada Border Box |
| strikethroughVertical | boolean | Garis coret vertikal pada Border Box |
| strikethroughBottomLeftToTopRight | boolean | Garis coret dari kiri bawah ke kanan atas pada Border Box |
| strikethroughTopLeftToBottomRight | boolean | Garis coret dari kiri atas ke kanan bawah pada Border Box |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - elemen kotak batas baru