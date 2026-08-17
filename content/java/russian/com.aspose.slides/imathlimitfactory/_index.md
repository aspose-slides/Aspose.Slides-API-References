---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create IMathLimit
type: docs
url: /ru/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Позволяет создать IMathLimit

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

Создает IMathLimit

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения предела |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Элемент предела |
| upperLimit | boolean | Устанавливает расположение предела сверху |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический предел
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```

Создает IMathLimit с пределом внизу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения предела |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Элемент предела |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический предел