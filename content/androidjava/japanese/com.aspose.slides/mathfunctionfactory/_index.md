---
title: MathFunctionFactory
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: 数学関数を作成できます
type: docs
url: /ja/com.aspose.slides/mathfunctionfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

数学関数を作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 数学関数を作成します |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | 数学関数を作成します |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


数学関数を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 関数名として使用される要素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の引数として使用される要素 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい数学関数
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


数学関数を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | java.lang.String | 関数名 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数の引数として使用される要素 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい数学関数