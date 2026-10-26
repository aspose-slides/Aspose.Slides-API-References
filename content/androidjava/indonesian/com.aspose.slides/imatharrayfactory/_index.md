---
title: IMathArrayFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Mengizinkan membuat array matematika
type: docs
url: /id/com.aspose.slides/imatharrayfactory/
---```
public interface IMathArrayFactory
```

Mengizinkan membuat array matematika

--------------------

Untuk kompatibilitas COM
## Metode

| Metode | Deskripsi |
| --- | --- |
| [createMathArray(IMathElement element)](#createMathArray-com.aspose.slides.IMathElement-) | Creates a math array and places the specified element in it |
| [createMathArray(IMathElementCollection elements)](#createMathArray-com.aspose.slides.IMathElementCollection-) | Creates a math array and places specified elements in it |
### createMathArray(IMathElement element) {#createMathArray-com.aspose.slides.IMathElement-}
```
public abstract IMathArray createMathArray(IMathElement element)
```


Creates a math array and places the specified element in it

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to place in array |

**Mengembalikan:**
[IMathArray](../../com.aspose.slides/imatharray) - array matematika baru
### createMathArray(IMathElementCollection elements) {#createMathArray-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathArray createMathArray(IMathElementCollection elements)
```


Creates a math array and places specified elements in it

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| elements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements to place in array |

**Mengembalikan:**
[IMathArray](../../com.aspose.slides/imatharray) - array matematika baru