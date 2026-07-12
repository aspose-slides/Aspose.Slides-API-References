---
title: MathPhantom
second_title: Java API リファレンス を介した Android 向け Aspose.Slides
description: 子要素のレイアウトに影響を与えるが、必ずしも表示しないファントム数式オブジェクト ltmphantgt を表します。
type: docs
url: /ja/com.aspose.slides/mathphantom/
---
**継承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

ファントム数式オブジェクト (<m:phant>) を表し、子要素のレイアウトに影響を与えますが、必ずしも表示されるわけではありません。ファントムは基底式を非表示にしながら、幅、高さ、または深さを保持して数式の整列やスペース確保を行うことができます。可視性やジオメトリの動作は、Show、ZeroWid、ZeroAsc、ZeroDesc、Transp などのプロパティで制御されます。

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // コンテンツを非表示にする
>  phantom.setZeroWidth(false);     // 幅を保持する
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | 指定されたベース数式要素を使用して、[MathPhantom](../../com.aspose.slides/mathphantom) クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getShow()](#getShow--) | ベース要素が表示されるかどうかを示す値を取得または設定します。 |
| [setShow(boolean value)](#setShow-boolean-) | ベース要素が表示されるかどうかを示す値を取得または設定します。 |
| [getZeroWidth()](#getZeroWidth--) | ベース要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | ベース要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getZeroAsc()](#getZeroAsc--) | ベース要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | ベース要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getZeroDesc()](#getZeroDesc--) | ベース要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | ベース要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。 |
| [getTransp()](#getTransp--) | ファントムがクラスベースの間隔規則に対して透明であるかどうかを示す値を取得または設定します。 |
| [setTransp(boolean value)](#setTransp-boolean-) | ファントムがクラスベースの間隔規則に対して透明であるかどうかを示す値を取得または設定します。 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | 子要素を取得 |

### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

指定されたベース数式要素を使用して、[MathPhantom](../../com.aspose.slides/mathphantom) クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ファントムが可視性とレイアウトを制御するベース [IMathElement](../../com.aspose.slides/imathelement)。この要素は、非表示または表示される可能性があるコンテンツを定義しながら、周囲の数式の幾何学的配置に影響を与えます。 |

--------------------

ファントム要素は、ベース式の視覚的スペースを確保または抑制するために使用され、必ずしも表示されるわけではありません。これは OMML 要素 <m:phant> に対応します。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

ベース引数

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

ベース要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、ベース要素は非表示になりますが、他のファントム設定に応じてスペースを占有することがあります。これは OMML 属性 m:show に対応します。

**戻り値:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

ベース要素が表示されるかどうかを示す値を取得または設定します。

--------------------

false の場合、ベース要素は非表示になりますが、他のファントム設定に応じてスペースを占有することがあります。これは OMML 属性 m:show に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

ベース要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムはベースの水平スペースを確保しません。これは OMML 属性 m:zeroWid に対応します。

**戻り値:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

ベース要素の幅をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムはベースの水平スペースを確保しません。これは OMML 属性 m:zeroWid に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

ベース要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムは周囲の数式行のベースラインを上げません。これは OMML 属性 m:zeroAsc に対応します。

**戻り値:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

ベース要素の上昇（ベースライン上の高さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムは周囲の数式行のベースラインを上げません。これは OMML 属性 m:zeroAsc に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

ベース要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムは周囲の数式行のベースラインを下げません。これは OMML 属性 m:zeroDesc に対応します。

**戻り値:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

ベース要素の下降（ベースライン下の深さ）をゼロとして扱うかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントムは周囲の数式行のベースラインを下げません。これは OMML 属性 m:zeroDesc に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

ファントムがクラスベースの間隔規則に対して透明であるかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントム内部の演算子や記号はファントムの周囲の数式間隔にまだ影響し（可視であるかのように）します。false の場合、クラスベースの間隔は無視されます。これは OMML 属性 m:transp に対応します。

**戻り値:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

ファントムがクラスベースの間隔規則に対して透明であるかどうかを示す値を取得または設定します。

--------------------

true の場合、ファントム内部の演算子や記号はファントムの周囲の数式間隔にまだ影響し（可視であるかのように）します。false の場合、クラスベースの間隔は無視されます。これは OMML 属性 m:transp に対応します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]