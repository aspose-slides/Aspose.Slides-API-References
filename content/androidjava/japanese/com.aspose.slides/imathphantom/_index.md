---
title: IMathPhantom
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 子要素のレイアウトに影響を与える phantom 数式オブジェクト ltmphantgt を表しますが、必ずしも表示されるわけではありません。
type: docs
url: /ja/com.aspose.slides/imathphantom/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

phantom 数式オブジェクト (<m:phant>) を表し、子要素のレイアウトに影響を与えますが、必ずしも表示されるわけではありません。phantom は基本式を非表示にしながら、幅、高さ、または深さを保持して数式を揃えたり空間を確保したりできます。表示や幾何形状の動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // コンテンツを非表示にする
>  phantom.setZeroWidth(false);     // 幅を保持する
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getShow()](#getShow--) | 基本要素が表示されるかどうかを示す値を取得または設定します。 |
| [setShow(boolean value)](#setShow-boolean-) | 基本要素が表示されるかどうかを示す値を取得または設定します。 |
| [getZeroWidth()](#getZeroWidth--) | 基本要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 基本要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getZeroAsc()](#getZeroAsc--) | 基本要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 基本要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getZeroDesc()](#getZeroDesc--) | 基本要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 基本要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getTransp()](#getTransp--) | クラスベースのスペーシング規則に対して phantom が透過的であるかどうかを示す値を取得または設定します。 |
| [setTransp(boolean value)](#setTransp-boolean-) | クラスベースのスペーシング規則に対して phantom が透過的であるかどうかを示す値を取得または設定します。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基本引数

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
```

**戻り値:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

基本要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、基本要素は非表示になりますが、他の phantom 設定に応じてスペースを占有することがあります。OMML 属性 m:show に対応します。

**戻り値:**  
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

基本要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、基本要素は非表示になりますが、他の phantom 設定に応じてスペースを占有することがあります。OMML 属性 m:show に対応します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

基本要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は基本要素の横方向のスペースを確保しません。OMML 属性 m:zeroWid に対応します。

**戻り値:**  
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

基本要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は基本要素の横方向のスペースを確保しません。OMML 属性 m:zeroWid に対応します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

基本要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は周囲の数式行のベースラインを上げません。OMML 属性 m:zeroAsc に対応します。

**戻り値:**  
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

基本要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は周囲の数式行のベースラインを上げません。OMML 属性 m:zeroAsc に対応します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

基本要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は周囲の数式行のベースラインを下げません。OMML 属性 m:zeroDesc に対応します。

**戻り値:**  
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

基本要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom は周囲の数式行のベースラインを下げません。OMML 属性 m:zeroDesc に対応します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

クラスベースのスペーシング規則に対して phantom が透過的であるかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom 内の演算子や記号は phantom 周囲の数式スペーシングに影響します（可視であるかのように）。false の場合、クラスベースのスペーシングは無視されます。OMML 属性 m:transp に対応します。

**戻り値:**  
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

クラスベースのスペーシング規則に対して phantom が透過的であるかどうかを示す値を取得または設定します。

--------------------

true の場合、phantom 内の演算子や記号は phantom 周囲の数式スペーシングに影響します（可視であるかのように）。false の場合、クラスベースのスペーシングは無視されます。OMML 属性 m:transp に対応します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |