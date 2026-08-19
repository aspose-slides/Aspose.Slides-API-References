---
title: IMathFunctionFactory
second_title: Referensi API Aspose.Slides untuk Java
description: Memungkinkan membuat fungsi matematika
type: docs
url: /id/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Memungkinkan membuat fungsi matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Method | Description |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Membuat fungsi matematika |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Membuat fungsi matematika |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Membuat fungsi matematika

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai nama fungsi |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai argumen fungsi |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - fungsi matematika baru
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Membuat fungsi matematika

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| funcName | java.lang.String | Nama fungsi |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemen yang digunakan sebagai argumen fungsi |

**Returns:**
[IMathFunction](../../com.aspose.slides/imathfunction) - fungsi matematika baru