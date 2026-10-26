---
title: MathematicalText
second_title: Java API リファレンス（Android 用 Aspose.Slides）
description: 数学テキスト
type: docs
url: /ja/com.aspose.slides/mathematicaltext/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装しているすべてのインターフェイス:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Mathematical text

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | デフォルトコンストラクタ（String.Empty の値を作成） |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | 単一記号で MathText を作成 |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | テキストから MathematicalText を作成 |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | テキストと書式設定から MathematicalText を作成 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | テキスト値 |
| [setValue(String value)](#setValue-java.lang.String-) | テキスト値 |
| [getFormat()](#getFormat--) | テキスト書式設定プロパティ |
| [getChildren()](#getChildren--) | 子要素を取得 |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


デフォルトコンストラクタ（String.Empty の値を作成）

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


単一記号で MathText を作成

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathSymbol | char | 単一記号 |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


テキストから MathematicalText を作成

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


テキストと書式設定から MathematicalText を作成

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| mathText | java.lang.String | テキスト値 |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | テキスト書式設定 |

### getValue() {#getValue--}
```
public final String getValue()
```


テキスト値

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**戻り値:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


テキスト値

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


テキスト書式設定プロパティ

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**戻り値:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]