---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API 參考文件
description: 允許建立數學分數
type: docs
url: /zh-hant/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

允許建立數學分數

--------------------

為 COM 相容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 建立數學分數 |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學分數 |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

建立數學分數

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型 |

**回傳值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

建立數學分數

**參數:**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**回傳值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數 [IMathFraction](../../com.aspose.slides/imathfraction)