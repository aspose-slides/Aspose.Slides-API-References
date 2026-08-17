---
title: IMathNaryOperator
second_title: Справочник API Aspose.Slides для Java
description: Определяет N-арный математический объект, такой как Summation и Integral.
type: docs
url: /ru/com.aspose.slides/imathnaryoperator/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), [com.aspose.slides.IMathNaryOperatorProperties](../../com.aspose.slides/imathnaryoperatorproperties)
```
public interface IMathNaryOperator extends IMathElement, IMathNaryOperatorProperties
```

Определяет N-арный математический объект, такой как Summation и Integral. Он состоит из оператора, базового (или операнда) аргумента и опциональных верхних и нижних пределов. Примеры N-арных операторов: Summation, Union, Intersection, Integral

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
| [getSubscript()](#getSubscript--) | Указывает аргумент нижнего индекса, который, например, в случае интеграла, задает нижний предел |
| [getSuperscript()](#getSuperscript--) | Указывает аргумент верхнего индекса, который, например, в случае интеграла, задает верхний предел |
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

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

Указывает аргумент нижнего индекса, который, например, в случае интеграла, задает нижний предел

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public abstract IMathElement getSuperscript()
```

Указывает аргумент верхнего индекса, который, например, в случае интеграла, задает верхний предел

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)