---
title: IMathNaryOperator
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет N-арный математический объект, такой как Summation и Integral.
type: docs
url: /ru/com.aspose.slides/imathnaryoperator/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Определяет N-арный математический объект, такой как суммирование и интеграл. Он состоит из оператора, базового аргумента (или операнда) и необязательных верхних и нижних пределов. Примеры N-арных операторов: Summation, Union, Intersection, Integral

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getSubscript()](#getSubscript--) | Указывает аргумент индекса, который, например, в случае интеграла задаёт нижний предел |
| [getSuperscript()](#getSuperscript--) | Указывает аргумент верхнего индекса, который, например, в случае интеграла задаёт верхний предел |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
>  ```


**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Указывает аргумент индекса, который, например, в случае интеграла задаёт нижний предел

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Указывает аргумент верхнего индекса, который, например, в случае интеграла задаёт верхний предел

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
>  ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)