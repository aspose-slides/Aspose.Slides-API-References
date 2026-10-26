---
title: IMathPhantom
second_title: Aspose.Slides の Java API リファレンス
description: ltmphantgt というファントム数式オブジェクトを表し、子要素のレイアウトに影響を与えますが、必ずしも表示されるわけではありません。
type: docs
url: /ja/com.aspose.slides/imathphantom/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

Phantom 数式オブジェクト (<m:phant>) を表し、必ずしも表示せずに子要素のレイアウトに影響を与えます。Phantom はベース式を非表示にしながら、幅・高さ・奥行きを保持して式を揃えたりスペースを確保したりできます。可視性や几何学的動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp といったプロパティで制御されます。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // コンテンツを非表示にする
>  phantom.setZeroWidth(false);     // 幅を保持する
>  ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getShow()](#getShow--) | ベース要素が表示されるかどうかを示す値を取得または設定します。 |
| [setShow(boolean value)](#setShow-boolean-) | ベース要素が表示されるかどうかを示す値を取得または設定します。 |
| [getZeroWidth()](#getZeroWidth--) | ベース要素の幅を 0 とみなすかどうかを示す値を取得または設定します。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | ベース要素の幅を 0 とみなすかどうかを示す値を取得または設定します。 |
| [getZeroAsc()](#getZeroAsc--) | ベース要素の上昇部 (基線上の高さ) を 0 とみなすかどうかを示す値を取得または設定します。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | ベース要素の上昇部 (基線上の高さ) を 0 とみなすかどうかを示す値を取得または設定します。 |
| [getZeroDesc()](#getZeroDesc--) | ベース要素の下降部 (基線下の深さ) を 0 とみなすかどうかを示す値を取得または設定します。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | ベース要素の下降部 (基線下の深さ) を 0 とみなすかどうかを示す値を取得または設定します。 |
| [getTransp()](#getTransp--) | クラスベースの間隔規則に対して Phantom が透過的であるかどうかを示す値を取得または設定します。 |
| [setTransp(boolean value)](#setTransp-boolean-) | クラスベースの間隔規則に対して Phantom が透過的であるかどうかを示す値を取得または設定します。 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```


**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

ベース要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、ベース要素は非表示になりますが、他の Phantom 設定に応じてスペースを占有することがあります。OMML 属性 m:show に対応します。

**戻り値:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

ベース要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、ベース要素は非表示になりますが、他の Phantom 設定に応じてスペースを占有することがあります。OMML 属性 m:show に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

ベース要素の幅を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom はベースの水平スペースを確保しません。OMML 属性 m:zeroWid に対応します。

**戻り値:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

ベース要素の幅を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom はベースの水平スペースを確保しません。OMML 属性 m:zeroWid に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

ベース要素の上昇部 (基線上の高さ) を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom は周囲の数式行の基線を上げません。OMML 属性 m:zeroAsc に対応します。

**戻り値:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

ベース要素の上昇部 (基線上の高さ) を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom は周囲の数式行の基線を上げません。OMML 属性 m:zeroAsc に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

ベース要素の下降部 (基線下の深さ) を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom は周囲の数式行の基線を下げません。OMML 属性 m:zeroDesc に対応します。

**戻り値:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

ベース要素の下降部 (基線下の深さ) を 0 とみなすかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom は周囲の数式行の基線を下げません。OMML 属性 m:zeroDesc に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

Phantom がクラスベースの間隔規則に対して透過的であるかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom 内の演算子や記号は可視状態と同様に周囲の数式間隔に影響します。false の場合、クラスベースの間隔は無視されます。OMML 属性 m:transp に対応します。

**戻り値:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

Phantom がクラスベースの間隔規則に対して透過的であるかどうかを示す値を取得または設定します。

--------------------

true の場合、Phantom 内の演算子や記号は可視状態と同様に周囲の数式間隔に影響します。false の場合、クラスベースの間隔は無視されます。OMML 属性 m:transp に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |