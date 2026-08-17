---
title: IMathFraction
second_title: Aspose.Slides Java API 参考
description: 指定由分子和分母组成的分数对象，二者之间以分数线分隔。
type: docs
url: /zh/com.aspose.slides/imathfraction/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

指定分数对象，由分子和分母组成，它们之间用分数线分隔。分数线可以是水平的或对角的，取决于分数属性。分数对象也用于表示堆叠函数，该函数将一个元素放在另一个元素之上，没有分数线。

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFractionType()](#getFractionType--) | 分数类型 默认: Bar |
| [setFractionType(int value)](#setFractionType-int-) | 分数类型 默认: Bar |
| [getNumerator()](#getNumerator--) | 分子 |
| [getDenominator()](#getDenominator--) | 分母 |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


分数类型 默认: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**返回：**
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```


分数类型 默认: Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getNumerator() {#getNumerator--}
```
public abstract IMathElement getNumerator()
```


分子

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public abstract IMathElement getDenominator()
```


分母

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)