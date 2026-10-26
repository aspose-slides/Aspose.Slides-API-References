---
title: MathLimitFactory
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: IMathLimit oluşturulmasına izin verir
type: docs
url: /tr/com.aspose.slides/mathlimitfactory/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

IMathLimit oluşturulmasına izin verir

--------------------

COM uyumluluğu için
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | IMathLimit oluşturur |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Alt limitte IMathLimit oluşturur |
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
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Limiti uygulamak için temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |
| upperLimit | boolean | Limitin üstte yer almasını ayarlar |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik limiti
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Alt limitte IMathLimit oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Limiti uygulamak için temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |

**Dönüş Değeri:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik limiti