---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math function
type: docs
url: /tr/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Matematik fonksiyonu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Matematik fonksiyonu oluşturur |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Matematik fonksiyonu oluşturur |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Matematik fonksiyonu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon adı olarak kullanılan öğe |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon bağımsız değişkeni olarak kullanılan öğe |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - yeni matematik fonksiyonu
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Matematik fonksiyonu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | java.lang.String | Fonksiyon adı |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon bağımsız değişkeni olarak kullanılan öğe |

**Döndürür:**
[IMathFunction](../../com.aspose.slides/imathfunction) - yeni matematik fonksiyonu