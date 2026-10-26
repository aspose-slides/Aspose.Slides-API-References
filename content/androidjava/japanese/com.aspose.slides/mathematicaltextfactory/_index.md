---
title: MathematicalTextFactory
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: MathematicalText 要素の作成を可能にします
type: docs
url: /ja/com.aspose.slides/mathematicaltextfactory/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)  
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

MathematicalText 要素の作成を可能にします

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 空の数学テキスト要素を作成 |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 指定された値で数学テキスト要素を作成 |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 指定された値で空の数学テキスト要素を作成 |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 指定された値と書式設定プロパティで空の数学テキスト要素を作成 |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```

### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```

空の数学テキスト要素を作成

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```

指定された値で数学テキスト要素を作成

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char | テキスト値として使用する単一シンボル |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```

指定された値で空の数学テキスト要素を作成

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

指定された値と書式設定プロパティで空の数学テキスト要素を作成

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | テキスト書式設定 |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text