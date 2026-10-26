---
title: IMathLimitFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathLimit
type: docs
url: /pl/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Umożliwia utworzenie IMathLimit

--------------------

Dla kompatybilności COM
## Metody

| Metoda | Opis |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Tworzy IMathLimit

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |
| upperLimit | boolean | Ustawia położenie limitu na górze |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nowy limit matematyczny
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Tworzy IMathLimit z limitem na dole

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy, do którego zastosować limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nowy limit matematyczny