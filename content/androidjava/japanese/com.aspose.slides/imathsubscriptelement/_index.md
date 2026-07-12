---
title: IMathSubscriptElement
second_title: Java API リファレンス（Android 用 Aspose.Slides）
description: ベースと右下に配置された縮小サイズの下付き文字からなる下付きオブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/imathsubscriptelement/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathSubscriptElement extends IMathElement
```

ベースと右下に配置された縮小サイズの下付き文字からなる下付きオブジェクトを指定します。

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getSubscript()](#getSubscript--) | 下付き文字 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement baseElem = subscriptElement.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public abstract IMathElement getSubscript()
```

下付き文字

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
>  IMathElement sub = subscriptElement.getSubscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)