--- 
title: MathFraction
second_title: Aspose.Slides Java API 参考
description: 指定由分子和分母通过分数线分隔组成的分数对象。
type: docs
url: /zh/com.aspose.slides/mathfraction/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathFraction](../../com.aspose.slides/imathfraction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFraction extends MathElementBase implements IMathFraction, IHasControlCharacterProperties
```

指定分数对象，由分子和分母通过分数线分隔组成。分数线可以是水平的或对角的，取决于分数属性。分数对象还用于表示堆叠函数，该函数将一个元素放在另一个元素之上，且没有分数线。

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 使用指定的 numerator、denominator 和 type 初始化 MathFraction |
| [MathFraction(IMathElement numerator, IMathElement denominator)](#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 使用指定的 numerator 和 denominator 初始化类型为 'Bar' 的 MathFraction |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFractionType()](#getFractionType--) | 分数类型 默认：Bar |
| [setFractionType(int value)](#setFractionType-int-) | 分数类型 默认：Bar |
| [getNumerator()](#getNumerator--) | Numerator |
| [getDenominator()](#getDenominator--) | Denominator |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public MathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


使用指定的 numerator、denominator 和 type 初始化 MathFraction

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |
| fractionType | int | Fraction type |

### MathFraction(IMathElement numerator, IMathElement denominator) {#MathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFraction(IMathElement numerator, IMathElement denominator)
```


使用指定的 numerator 和 denominator 初始化类型为 'Bar' 的 MathFraction

--------------------

> ```
> Example:
>  
>  MathFraction mathFraction = new MathFraction(new MathematicalText("x"), new MathematicalText("y"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | Numerator |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Denominator |

### getFractionType() {#getFractionType--}
```
public final int getFractionType()
```


分数类型 默认：Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**返回值：**
int
### setFractionType(int value) {#setFractionType-int-}
```
public final void setFractionType(int value)
```


分数类型 默认：Bar

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
public final IMathElement getNumerator()
```


Numerator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement numerator = mathFraction.getNumerator();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getDenominator() {#getDenominator--}
```
public final IMathElement getDenominator()
```


Denominator

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathElement denominator = mathFraction.getDenominator();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


获取子元素

**返回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Control Character Properties

**返回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps