---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create IMathNaryOperator
type: docs
url: /ja/com.aspose.slides/imathnaryoperatorfactory/
---```
public interface IMathNaryOperatorFactory
```

IMathNaryOperator を作成できます

--------------------

COM互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

IMathNaryOperator を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基底引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新しい IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

IMathNaryOperator を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基底引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新しい IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public abstract IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

IMathNaryOperator を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基底引数 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - 新しい IMathNaryOperator