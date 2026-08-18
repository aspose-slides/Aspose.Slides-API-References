---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Umożliwia tworzenie IMathLimit
type: docs
url: /pl/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Umożliwia tworzenie IMathLimit

--------------------

Dla zgodności z COM
## Metody

| Method | Description |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Tworzy IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Tworzy IMathLimit z limitem na dole |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```

Tworzy IMathLimit

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy do zastosowania limitu |
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
| Parameter | Type | Description |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argument bazowy do zastosowania limitu |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Element limitu |

**Zwraca:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nowy limit matematyczny