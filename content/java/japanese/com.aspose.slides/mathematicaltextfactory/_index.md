---
title: MathematicalTextFactory
second_title: Java 用 Aspose.Slides API リファレンス
description: MathematicalText 要素を作成できます
type: docs
url: /ja/com.aspose.slides/mathematicaltextfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

MathematicalText 要素を作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 空の数式テキスト要素を作成します |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 指定された値で数式テキスト要素を作成します |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 指定された値で空の数式テキスト要素を作成します |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 指定された値と書式設定プロパティで空の数式テキスト要素を作成します |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


空の数式テキスト要素を作成します

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


指定された値で数式テキスト要素を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char | テキスト値として使用する単一のシンボル |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


指定された値で空の数式テキスト要素を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


指定された値と書式設定プロパティで空の数式テキスト要素を作成します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | テキストの書式設定 |

**戻り値:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - 新しい Mathematical Text