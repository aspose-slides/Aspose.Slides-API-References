---
title: MathSubscriptElement
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: ベースと、右下に配置された縮小サイズの下付文字から構成される下付オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathsubscriptelement/
---
**継承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase), [com.aspose.slides.BaseScript](../../com.aspose.slides/basescript)

**すべての実装インターフェイス:**  
[com.aspose.slides.IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)  
```
public final class MathSubscriptElement extends BaseScript implements IMathSubscriptElement
```

ベースと、右下に配置された縮小サイズの下付文字から構成される下付オブジェクトを指定します。

--------------------

> ```
> Example:
>  
>  IMathSubscriptElement subscriptElement = new MathematicalText("N").setSubscript("i");
> ```
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [MathSubscriptElement(IMathElement baseArg, IMathElement subScript)](#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathSubscriptElement クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSubscript()](#getSubscript--) | 下付文字 |
| [getChildren()](#getChildren--) | 子要素を取得 |
### MathSubscriptElement(IMathElement baseArg, IMathElement subScript) {#MathSubscriptElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathSubscriptElement(IMathElement baseArg, IMathElement subScript)
```

MathSubscriptElement クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("X");
>  IMathElement subscript = new MathematicalText("i");
>  MathSubscriptElement subscriptElement = new MathSubscriptElement(baseElement, subscript);
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) |  |
| subScript | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

下付文字

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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得

**戻り値:**  
com.aspose.slides.IMathElement[]