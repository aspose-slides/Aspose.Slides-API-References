---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: MathematicalText 要素の作成を可能にします
type: docs
url: /ja/com.aspose.slides/imathematicaltextfactory/
---``` 
public interface IMathematicalTextFactory
```

MathematicalText 要素の作成を可能にします

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | 空の数学テキスト要素を作成します |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | 指定された値で数学テキスト要素を作成します |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | 指定された値で空の数学テキスト要素を作成します |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | 指定された値と書式設定プロパティで空の数学テキスト要素を作成します |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

空の数学テキスト要素を作成します

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

指定された値で数学テキスト要素を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char | テキスト値として使用する単一のシンボル |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

指定された値で空の数学テキスト要素を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

指定された値と書式設定プロパティで空の数学テキスト要素を作成します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | テキスト書式設定 |

**戻り値:**  
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text