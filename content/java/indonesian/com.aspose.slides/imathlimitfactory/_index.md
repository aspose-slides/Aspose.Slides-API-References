---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathLimit
type: docs
url: /id/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Memungkinkan membuat IMathLimit

--------------------

Untuk kompatibilitas COM
## Metode

| Method | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Membuat IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat IMathLimit dengan limit di bagian bawah |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Membuat IMathLimit

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen limit |
| upperLimit | boolean | Menetapkan penempatan limit di atas |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Membuat IMathLimit dengan limit di bagian bawah

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argumen dasar untuk menerapkan limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemen limit |

**Mengembalikan:**
[IMathLimit](../../com.aspose.slides/imathlimit) - batas matematika baru