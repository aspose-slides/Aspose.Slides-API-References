---
title: MathLimitFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создавать IMathLimit
type: docs
url: /ru/com.aspose.slides/mathlimitfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Позволяет создать IMathLimit

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Создает IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает IMathLimit с лимитом внизу |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Создает IMathLimit

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения лимита |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Элемент лимита |
| upperLimit | boolean | Устанавливает размещение лимита сверху |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический лимит
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Создает IMathLimit с лимитом внизу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Базовый аргумент для применения лимита |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Элемент лимита |

**Возвращаемое значение:**
[IMathLimit](../../com.aspose.slides/imathlimit) - новый математический лимит