---
title: IMathFractionFactory
second_title: Aspose.Slides for Android via Java API 参考
description: 允许创建数学分数
type: docs
url: /zh/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

允许创建数学分数

--------------------

用于 COM 兼容性
## 方法

| 方法 | 描述 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 创建数学分数 |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 创建数学分数 |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```

创建数学分数

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数类型 |

**返回值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新数学分数 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```

创建数学分数

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**返回值:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新数学分数 [IMathFraction](../../com.aspose.slides/imathfraction)