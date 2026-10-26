---
title: IMathLimitFactory
second_title: Aspose.Slides для Android через Java API Reference
description: Позволяет создавать IMathLimit
type: docs
url: /ru/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Позволяет создавать IMathLimit

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Creates IMathLimit

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |
| upperLimit | boolean | Sets the placement of the limit on top |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический предел
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Creates IMathLimit with limit at the bottom

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Base argument to apply the limit |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Limit element |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический предел