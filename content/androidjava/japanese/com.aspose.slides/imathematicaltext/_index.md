---
title: IMathematicalText
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 数学テキスト
type: docs
url: /ja/com.aspose.slides/imathematicaltext/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

数学テキスト

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | テキスト値 |
| [setValue(String value)](#setValue-java.lang.String-) | テキスト値 |
| [getFormat()](#getFormat--) | テキスト書式設定プロパティ |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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