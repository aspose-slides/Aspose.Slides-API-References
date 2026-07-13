---
title: MathLimitFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mengizinkan pembuatan IMathLimit
type: docs
url: /id/com.aspose.slides/mathlimitfactory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Mengizinkan pembuatan IMathLimit

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Membuat IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathLimit dengan limit di bagian bawah |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Membuat IMathLimit

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen limit |
| upperLimit | boolean | Menentukan penempatan limit di atas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Membuat IMathLimit dengan limit di bagian bawah

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen limit |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru