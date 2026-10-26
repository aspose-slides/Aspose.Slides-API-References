---
title: MathPhantom
second_title: Aspose.Slides for Java API リファレンス
description: 子要素のレイアウトに影響を与えるが、必ずしも表示しないファントム数式オブジェクト ltmphantgt を表します。
type: docs
url: /ja/com.aspose.slides/mathphantom/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

基底要素を必ずしも表示せずに子要素のレイアウトに影響を与えるファントム数式オブジェクト (<m:phant>) を表します。ファントムは幅・高さ・奥行きを保持したまま基底式を非表示にでき、数式の整列や空間確保に使用されます。表示状態や幾何形状の動作は Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。

--------------------
> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // コンテンツを非表示にする
>  phantom.setZeroWidth(false);     // 幅を保持する
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 指定された基底数式要素を使用して [MathPhantom](../../com.aspose.slides/mathphantom) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基底引数 |
| [getShow()](#getShow--) | 基底要素が表示されるかどうかを示す値を取得または設定します。 |
| [setShow(boolean value)](#setShow-boolean-) | 基底要素が表示されるかどうかを示す値を取得または設定します。 |
| [getZeroWidth()](#getZeroWidth--) | 基底要素の幅をゼロとみなすかどうかを示す値を取得または設定します。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | 基底要素の幅をゼロとみなすかどうかを示す値を取得または設定します。 |
| [getZeroAsc()](#getZeroAsc--) | 基底要素の上昇部 (ベースライン上の高さ) をゼロとみなすかどうかを示す値を取得または設定します。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | 基底要素の上昇部 (ベースライン上の高さ) をゼロとみなすかどうかを示す値を取得または設定します。 |
| [getZeroDesc()](#getZeroDesc--) | 基底要素の下降部 (ベースライン下の深さ) をゼロとみなすかどうかを示す値を取得または設定します。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | 基底要素の下降部 (ベースライン下の深さ) をゼロとみなすかどうかを示す値を取得または設定します。 |
| [getTransp()](#getTransp--) | クラスベースの間隔規則に対してファントムが透過的かどうかを示す値を取得または設定します。 |
| [setTransp(boolean value)](#setTransp-boolean-) | クラスベースの間隔規則に対してファントムが透過的かどうかを示す値を取得または設定します。 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
| [getChildren()](#getChildren--) | 子要素を取得します |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

指定された基底数式要素を使用して [MathPhantom](../../com.aspose.slides/mathphantom) クラスの新しいインスタンスを初期化します。

--------------------
> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 可視性とレイアウトがファントムによって制御される基底 [IMathElement](../../com.aspose.slides/imathelement)。この要素は非表示または表示される可能性があるが、周囲の数式の幾何的整列には影響を与える。 |

ファントム要素は、基底式の視覚的領域を予約または抑制するために使用され、必ずしも表示されるわけではありません。OMML 要素 <m:phant> に対応します。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基底引数

--------------------
> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

基底要素が表示されるかどうかを示す値を取得または設定します。

--------------------
false の場合、基底要素は非表示になるが、他のファントム設定に応じてスペースを占有することがある。OMML 属性 m:show に対応します。

**戻り値:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

基底要素が表示されるかどうかを示す値を取得または設定します。

--------------------
false の場合、基底要素は非表示になるが、他のファントム設定に応じてスペースを占有することがある。OMML 属性 m:show に対応します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

基底要素の幅をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは基底の水平スペースを確保しません。OMML 属性 m:zeroWid に対応します。

**戻り値:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

基底要素の幅をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは基底の水平スペースを確保しません。OMML 属性 m:zeroWid に対応します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

基底要素の上昇部 (ベースライン上の高さ) をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは周囲の数式行のベースラインを上げません。OMML 属性 m:zeroAsc に対応します。

**戻り値:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

基底要素の上昇部 (ベースライン上の高さ) をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは周囲の数式行のベースラインを上げません。OMML 属性 m:zeroAsc に対応します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

基底要素の下降部 (ベースライン下の深さ) をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは周囲の数式行のベースラインを下げません。OMML 属性 m:zeroDesc に対応します。

**戻り値:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

基底要素の下降部 (ベースライン下の深さ) をゼロとみなすかどうかを示す値を取得または設定します。

--------------------
true の場合、ファントムは周囲の数式行のベースラインを下げません。OMML 属性 m:zeroDesc に対応します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

ファントムがクラスベースの間隔規則に対して透過的かどうかを示す値を取得または設定します。

--------------------
true の場合、ファントム内部の演算子や記号はファントムが可視であるかのように間隔に影響します。false の場合、クラスベースの間隔は無視されます。OMML 属性 m:transp に対応します。

**戻り値:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

ファントムがクラスベースの間隔規則に対して透過的かどうかを示す値を取得または設定します。

--------------------
true の場合、ファントム内部の演算子や記号はファントムが可視であるかのように間隔に影響します。false の場合、クラスベースの間隔は無視されます。OMML 属性 m:transp に対応します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得します

**戻り値:**
com.aspose.slides.IMathElement[]