---
title: IMathFractionFactory
second_title: Aspose.Slides for Android の Java API リファレンス
description: 数学分数を作成できます
type: docs
url: /ja/com.aspose.slides/imathfractionfactory/
---```
public interface IMathFractionFactory
```

数学分数を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Creates a math fraction |
| [createMathFraction(IMathElement numerator, IMathElement denominator)](#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates a math fraction |
### createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator, int fractionType)
```


数学分数を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |
| fractionType | int | 分数タイプ |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい数学分数 [IMathFraction](../../com.aspose.slides/imathfraction)
### createMathFraction(IMathElement numerator, IMathElement denominator) {#createMathFraction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFraction createMathFraction(IMathElement numerator, IMathElement denominator)
```


数学分数を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| numerator | [IMathElement](../../com.aspose.slides/imathelement) | 分子 |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | 分母 |

**戻り値:**
[IMathFraction](../../com.aspose.slides/imathfraction) - 新しい数学分数 [IMathFraction](../../com.aspose.slides/imathfraction)