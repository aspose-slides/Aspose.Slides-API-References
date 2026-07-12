---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /ja/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

数式区切り文字を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | 要素に適用して数式区切り文字を作成 |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | 要素に適用して数式区切り文字を作成 |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

要素に適用して数式区切り文字を作成

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 区切り文字を適用する数式要素 |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新しい数式区切り文字
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

要素に適用して数式区切り文字を作成

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | 区切り文字を適用する数式要素のコレクション |

**戻り値:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - 新しい数式区切り文字