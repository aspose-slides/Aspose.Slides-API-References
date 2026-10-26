---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /tr/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

IMathLimit oluşturulmasını sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Method | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


IMathLimit oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Limit uygulanacak temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |
| upperLimit | boolean | Limitin üstte yer almasını ayarlar |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik limiti
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Altında limit ile IMathLimit oluşturur

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Limit uygulanacak temel argüman |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit öğesi |

**Döndürür:**
[IMathLimit](../../com.aspose.slides/imathlimit) - yeni matematik limiti