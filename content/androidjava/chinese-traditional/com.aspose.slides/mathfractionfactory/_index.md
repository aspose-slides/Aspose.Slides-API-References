---
title: MathFractionFactory
second_title: 適用於 Android 的 Aspose.Slides 透過 Java API 參考
description: 允許建立數學分數
type: docs
url: /zh-hant/com.aspose.slides/mathfractionfactory/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

允許建立數學分數

--------------------

用於 COM 相容性
## Constructors

| Constructor | Description |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 建立數學分數 |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 建立數學分數 |
### MathFractionFactory() {#MathFractionFactory--}
```
public MathFractionFactory()
```


### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


建立數學分數

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型 |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


建立數學分數

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**回傳值：**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數