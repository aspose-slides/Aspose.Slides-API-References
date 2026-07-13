---
title: MathFunctionFactory
second_title: Referensi API Java Aspose.Slides untuk Android
description: Memungkinkan membuat fungsi matematika
type: docs
url: /id/com.aspose.slides/mathfunctionfactory/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Memungkinkan membuat fungsi matematika

--------------------

Untuk kompatibilitas COM
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
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
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Membuat fungsi matematika

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| funcName | java.lang.String | Nama fungsi |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai argumen fungsi |

**Mengembalikan:**
[IMathFunction](../../com.aspose.slides/imathfunction) - fungsi matematika baru