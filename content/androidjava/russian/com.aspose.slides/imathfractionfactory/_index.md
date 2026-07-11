---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Позволяет создавать математическую дробь
type: docs
url: /ru/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

Позволяет создавать математическую дробь

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Создает математическую дробь |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает математическую дробь |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


Создает математическую дробь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Числитель |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |
| fractionType | int | Тип дроби |

**Возвращаемое значение:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Новая математическая дробь [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


Создает математическую дробь

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Числитель |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |

**Возвращаемое значение:**
[IMathFraction](../../com.aspose.slides/imathfraction) - Новая математическая дробь [IMathFraction](../../com.aspose.slides/imathfraction)