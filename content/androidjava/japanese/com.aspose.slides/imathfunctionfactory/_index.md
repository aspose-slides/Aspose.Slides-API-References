---
title: IMathFunctionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: 数学関数を作成することができます
type: docs
url: /ja/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

数学関数を作成することができます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates math function |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Creates math function |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```

数学関数を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | 関数名として使用される要素 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数引数として使用される要素 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい数学関数
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```

数学関数を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| funcName | java.lang.String | 関数名 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 関数引数として使用される要素 |

**戻り値:**
[IMathFunction](../../com.aspose.slides/imathfunction) - 新しい数学関数