---
title: MathFractionFactory
second_title: Aspose.Slides for Java API 參考
description: 允許建立數學分數
type: docs
url: /zh-hant/com.aspose.slides/mathfractionfactory/
---
**繼承**:
java.lang.Object

**所有已實作介面**:
[com.aspose.slides.IMathFractionFactory](../../com.aspose.slides/imathfractionfactory)
```
public class MathFractionFactory implements IMathFractionFactory
```

允許建立數學分數

--------------------

供 COM 相容性使用
## 建構子

| 建構子 | 描述 |
| --- | --- |
| [MathFractionFactory()](#MathFractionFactory--) |  |
## 方法

| 方法 | 描述 |
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

**參數**:
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分數類型 |

**傳回值**:
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


建立數學分數

**參數**:
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**傳回值**:
[IMathFraction](../../com.aspose.slides/imathfraction) - 新的數學分數