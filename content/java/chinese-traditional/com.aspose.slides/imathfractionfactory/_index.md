---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math fraction
type: docs
url: /zh-hant/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

允許建立數學分數

--------------------

供 COM 相容性
## 方法

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

建立數學分數

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型 |

**返回值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

建立數學分數

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**返回值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數 [IMathFraction](../../com.aspose.slides/imathfraction)