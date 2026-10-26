---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Umožňuje vytvořit IMathLimit
type: docs
url: /cs/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Umožňuje vytvořit IMathLimit

--------------------

Pro kompatibilitu s COM
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Creates IMathLimit

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument, na který se aplikuje limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Prvek limitu |
| upperLimit | boolean | Nastavuje umístění limitu nahoře |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - new math limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Creates IMathLimit with limit at the bottom

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument, na který se aplikuje limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Prvek limitu |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - new math limit