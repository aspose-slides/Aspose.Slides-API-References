---
title: MathLimitFactory
second_title: Aspose.Slides for Java API Referansı
description: IMathLimit oluşturmayı sağlar
type: docs
url: /tr/com.aspose.slides/mathlimitfactory/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

IMathLimit oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metodlar

| Metod | Açıklama |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit oluşturur |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Alt limitli IMathLimit oluşturur |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Sınırlamayı uygulamak için temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |
| upperLimit | boolean | Sınırlamanın üstte konumlandırılmasını ayarlar |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik sınırlaması
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Alt sınıra sahip IMathLimit oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Sınırlamayı uygulamak için temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik sınırlaması