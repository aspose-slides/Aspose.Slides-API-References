---
title: MathLimitFactory
second_title: Referensi API Aspose.Slides untuk Java
description: Memungkinkan membuat IMathLimit
type: docs
url: /id/com.aspose.slides/mathlimitfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Memungkinkan membuat IMathLimit

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
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathLimit dengan batas di bagian bawah |
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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan batas |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen batas |
| upperLimit | boolean | Menetapkan penempatan batas di atas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Membuat IMathLimit dengan batas di bagian bawah

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan batas |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru