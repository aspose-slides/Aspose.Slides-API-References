---
title: MathFractionFactory
second_title: Aspose.Slides для Java API Reference
description: Позволяет создать математическую дробь
type: docs
url: /ru/com.aspose.slides/mathfractionfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

Позволяет создать математическую дробь

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```

### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

Создает математическую дробь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Числитель |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |
| fractionType | int | Тип дроби |

**Возвращаемое значение:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая математическая дробь
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

Создает математическую дробь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Числитель |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |

**Возвращаемое значение:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая математическая дробь