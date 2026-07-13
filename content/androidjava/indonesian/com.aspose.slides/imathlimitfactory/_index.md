---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Memungkinkan membuat IMathLimit
type: docs
url: /id/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Memungkinkan membuat IMathLimit

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Membuat IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathLimit dengan batas di bagian bawah |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
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
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Membuat IMathLimit dengan batas di bagian bawah

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan batas |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen batas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru