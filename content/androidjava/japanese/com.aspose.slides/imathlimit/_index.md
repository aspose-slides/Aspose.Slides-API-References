---
title: IMathLimit
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ベースライン上のテキストと、その直上または直下にある縮小サイズのテキストで構成される Limit オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathlimit/
---
**実装されているすべてのインターフェース:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathLimit extends IMathElement
```

ベースライン上のテキストと、その直上または直下にある縮小サイズのテキストで構成される Limit オブジェクトを指定します。

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getLimit()](#getLimit--) | 制限引数 |
| [getUpperLimit()](#getUpperLimit--) | 上限または下限を指定します |
| [setUpperLimit(boolean value)](#setUpperLimit-boolean-) | 上限または下限を指定します |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基本引数

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement baseArg = limitElement.getBase();
> ```

**戻り値:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getLimit() {#getLimit--}
```
public abstract IMathElement getLimit()
```

制限引数

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  IMathElement limitArg = limitElement.getLimit();
> ```

**戻り値:**  
[IMathElement](../../com.aspose.slides/imathelement)

### getUpperLimit() {#getUpperLimit--}
```
public abstract boolean getUpperLimit()
```

上限または下限を指定します

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**戻り値:**  
boolean

### setUpperLimit(boolean value) {#setUpperLimit-boolean-}
```
public abstract void setUpperLimit(boolean value)
```

上限または下限を指定します

--------------------

> ```
> Example:
>  
>  IMathLimit limitElement = new MathLimit(new MathematicalText("lim"), new MathematicalText("�?\u2018\u203a�\u2020\u2019�\u02c6\u017e"));
>  limitElement.setUpperLimit(false);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |