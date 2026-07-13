---
title: MathLimitFactory
second_title: Aspose.Slides pro Android prostřednictvím Java referenční příručky API
description: Umožňuje vytvořit IMathLimit
type: docs
url: /cs/com.aspose.slides/mathlimitfactory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Umožňuje vytvořit IMathLimit

--------------------

Pro COM kompatibilitu
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Vytváří IMathLimit

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro aplikaci limitu |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Prvek limitu |
| upperLimit | boolean | Nastavuje umístění limitu nahoře |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nový matematický limit
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Vytváří IMathLimit s limitem dolů

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Základní argument pro aplikaci limitu |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Prvek limitu |

**Návratová hodnota:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nový matematický limit