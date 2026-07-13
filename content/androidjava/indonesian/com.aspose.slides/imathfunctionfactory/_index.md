---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math function
type: docs
url: /id/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Memungkinkan membuat fungsi matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Membuat fungsi matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai nama fungsi |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai argumen fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - fungsi matematika baru
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Membuat fungsi matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| funcName | java.lang.String | Nama fungsi |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai argumen fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - fungsi matematika baru