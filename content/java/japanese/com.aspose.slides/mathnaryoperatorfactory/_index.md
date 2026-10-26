---
title: MathNaryOperatorFactory
second_title: Aspose.Slides for Java API リファレンス
description: IMathNaryOperator を作成できます
type: docs
url: /ja/com.aspose.slides/mathnaryoperatorfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathNaryOperatorFactory](../../com.aspose.slides/imathnaryoperatorfactory)
```
public class MathNaryOperatorFactory implements IMathNaryOperatorFactory
```

IMathNaryOperator を作成できます

--------------------

COM 互換性のため
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathNaryOperatorFactory()](#MathNaryOperatorFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
| [createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#createMathNaryOperator-char-com.aspose.slides.IMathElement-) | IMathNaryOperator を作成します |
### MathNaryOperatorFactory() {#MathNaryOperatorFactory--}
```
public MathNaryOperatorFactory()
```


### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


IMathNaryOperator を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基本引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


IMathNaryOperator を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基本引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator
### createMathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#createMathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator createMathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


IMathNaryOperator を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | 演算子記号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 演算子を適用する基本引数 |

**戻り値:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - new IMathNaryOperator