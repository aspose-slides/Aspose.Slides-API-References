---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
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
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Vytvoří IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Vytvoří IMathLimit s limitem na spodní straně |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Vytvoří IMathLimit

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument, na který se aplikuje limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |
| upperLimit | boolean | Nastavuje umístění limitu nahoře |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nový matematický limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Vytvoří IMathLimit s limitem na spodní straně

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument, na který se aplikuje limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nový matematický limit