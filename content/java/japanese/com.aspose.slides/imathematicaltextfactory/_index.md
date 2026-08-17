---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API リファレンス
description: MathematicalText 要素を作成できます
type: docs
url: /ja/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

MathematicalText 要素を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 空の MathematicalText 要素を作成 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 指定された値で MathematicalText 要素を作成 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 指定された値で空の MathematicalText 要素を作成 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 指定された値と書式設定プロパティで空の MathematicalText 要素を作成 |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

空の MathematicalText 要素を作成

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

指定された値で MathematicalText 要素を作成

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char | テキスト値として使用する単一のシンボル |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

指定された値で空の MathematicalText 要素を作成

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

指定された値と書式設定プロパティで空の MathematicalText 要素を作成

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | テキスト形式設定 |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text