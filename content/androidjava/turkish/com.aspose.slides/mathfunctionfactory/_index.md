---
title: MathFunctionFactory
second_title: Aspose.Slides Android için Java API Referansı
description: Matematik fonksiyonu oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathfunctionfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Matematik fonksiyonu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Matematik fonksiyonu oluşturur |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Matematik fonksiyonu oluşturur |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```

### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

Matematik fonksiyonu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon adı olarak kullanılan öğe |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon argümanı olarak kullanılan öğe |

**Dönüş Değeri:**
[IMathFunction](../../com.aspose.slides/imathfunction) - yeni matematik fonksiyonu
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

Matematik fonksiyonu oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| funcName | java.lang.String | Fonksiyon adı |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Fonksiyon argümanı olarak kullanılan öğe |

**Dönüş Değeri:**
[IMathFunction](../../com.aspose.slides/imathfunction) - yeni matematik fonksiyonu