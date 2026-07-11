---
title: IMathFraction
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби.
type: docs
url: /ru/com.aspose.slides/imathfraction/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

Определяет объект дроби, состоящий из числителя и знаменателя, разделённых чертой дроби. Черта дроби может быть горизонтальной или диагональной, в зависимости от свойств дроби. Объект дроби также используется для представления функции стека, которая размещает один элемент над другим без черты дроби.

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getFractionType()](#getFractionType--) | Тип дроби по умолчанию: Bar |
| [setFractionType(int value)](#setFractionType-int-) | Тип дроби по умолчанию: Bar |
| [getNumerator()](#getNumerator--) | Числитель |
| [getDenominator()](#getDenominator--) | Знаменатель |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


Тип дроби по умолчанию: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Возвращаемое значение:**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


Тип дроби по умолчанию: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


Числитель

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


Знаменатель

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)