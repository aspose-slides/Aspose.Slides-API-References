---
title: IMathFractionFactory
second_title: Aspose.Slides for Java API Reference
description: 数式分数を作成できます
type: docs
url: /ja/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

数式分数を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | 数式分数を作成します |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 数式分数を作成します |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


数式分数を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数のタイプ |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい数式分数 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


数式分数を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい数式分数 [IMathFraction](../../com.aspose.slides/imathfraction)