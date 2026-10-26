---
title: IMathFraction
second_title: Aspose.Slides for Java API 參考
description: 指定分數物件，由分子和分母組成，以分數線分隔。
type: docs
url: /zh-hant/com.aspose.slides/imathfraction/
---
**所有已實作的介面:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathFraction extends IMathElement
```

指定分數物件，由分子和分母組成，兩者以分數線分隔。分數線可以是水平或對角，取決於分數屬性。分數物件亦可用於表示堆疊功能，將一個元素置於另一個之上，且不使用分數線。

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  IMathFraction mathFraction2 = new MathFraction(new MathematicalText("x"), new MathematicalText("y"), MathFractionTypes.Linear);
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [getFractionType()](#getFractionType--) | 分數類型 預設： Bar |
| [setFractionType(int value)](#setFractionType-int-) | 分數類型 預設： Bar |
| [getNumerator()](#getNumerator--) | 分子 |
| [getDenominator()](#getDenominator--) | 分母 |

### getFractionType() {#getFractionType--}
```
public abstract int getFractionType()
```

分數類型 預設： Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**返回:**  
int
### setFractionType(int value) {#setFractionType-int-}
```
public abstract void setFractionType(int value)
```

分數類型 預設： Bar

--------------------

> ```
> Example:
>  
>  IMathFraction mathFraction = new MathematicalText("x").divide("y");
>  mathFraction.setFractionType(MathFractionTypes.Linear);
> ```

**參數:**
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

**返回:**  
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

**返回:**  
[IMathElement](../../com.aspose.slides/imathelement)