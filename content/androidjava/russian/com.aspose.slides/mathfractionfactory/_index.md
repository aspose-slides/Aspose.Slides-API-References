---
title: MathFractionFactory
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет создавать математическую дробь
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

Позволяет создавать математическую дробь

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Создает математическую дробь |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает математическую дробь |
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