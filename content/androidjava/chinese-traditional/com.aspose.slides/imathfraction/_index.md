---
title: IMathFraction
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 指定分數物件，由分子與分母以分數線分隔。
type: docs
url: /zh-hant/com.aspose.slides/imathfraction/
---
**所有已實作介面：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

指定分數物件，由分子與分母以分數線分隔。分數線可以是水平或對角，取決於分數屬性。分數物件也用於表示堆疊函式，將一個元素放在另一個之上，且沒有分數線。

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
| [getFractionType()](#getFractionType--) | 分數類型 預設：Bar |
| [setFractionType(int value)](#setFractionType-int-) | 分數類型 預設：Bar |
| [getNumerator()](#getNumerator--) | 分子 |
| [getDenominator()](#getDenominator--) | 分母 |
### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```


分數類型 預設：Bar

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
public abstract void setFractionType(int value)
```


分數類型 預設：Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**參數：**
| 參數 | 類型 | 說明 |
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


**返回值：**
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

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)