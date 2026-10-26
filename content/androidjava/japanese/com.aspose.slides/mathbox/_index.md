---
title: MathBox
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 数学要素の論理的なボックス化（パッケージ化）を指定します。
type: docs
url: /ja/com.aspose.slides/mathbox/
---
**継承:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

数学要素の論理的なボックス化（パッケージ化）を指定します。例えば、ボックス化されたオブジェクトは、位置合わせポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、内部で改行を許可しないようにグループ化されたりします。例として、"==" 演算子は改行を防ぐためにボックス化すべきです。

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | 指定された要素を引数として MathBox を初期化します |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | 基本引数 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 演算子エミュレータ。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 演算子エミュレータ。 |
| [getNoBreak()](#getNoBreak--) | 改行なし このプロパティはオブジェクトボックスの "unbreakable" プロパティを指定します。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 改行なし このプロパティはオブジェクトボックスの "unbreakable" プロパティを指定します。 |
| [getDifferential()](#getDifferential--) | 微分 真の場合、ボックスは微分として機能し（例: \\ud835\\udc51\\ud835\\udc65 を積分子内で使用）、数学的微分に適切な水平間隔を受け取ります。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分 真の場合、ボックスは微分として機能し（例: \\ud835\\udc51\\ud835\\udc65 を積分子内で使用）、数学的微分に適切な水平間隔を受け取ります。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 真の場合、この演算子エミュレータは位置合わせポイントとして機能します。つまり、他の式で指定された位置合わせポイントと揃えることができます。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 真の場合、この演算子エミュレータは位置合わせポイントとして機能します。つまり、他の式で指定された位置合わせポイントと揃えることができます。 |
| [getExplicitBreak()](#getExplicitBreak--) | 明示的な改行 ボックスオブジェクトの開始位置で改行があるかどうかを指定し、行がボックスオブジェクトの開始位置で折り返されます。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 明示的な改行 ボックスオブジェクトの開始位置で改行があるかどうかを指定し、行がボックスオブジェクトの開始位置で折り返されます。 |
| [getChildren()](#getChildren--) | 子要素を取得 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

指定された要素を引数として MathBox を初期化します

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ボックスが適用される基本要素です。null にすることができます。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基本引数

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

演算子エミュレータ。true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。つまり、例えば、この文字は改行ポイントとして機能したり、他の演算子に合わせて位置合わせできることを意味します。演算子エミュレータは、'==' のように複数のグリフが結合して演算子を形成する場合に頻繁に使用されます。デフォルト値: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**戻り値:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

演算子エミュレータ。true の場合、ボックスとその内容は単一の演算子として動作し、演算子のプロパティを継承します。つまり、例えば、この文字は改行ポイントとして機能したり、他の演算子に合わせて位置合わせできることを意味します。演算子エミュレータは、'==' のように�数のグリフが結合して演算子を形成する場合に頻繁に使用されます。デフォルト値: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

改行なし このプロパティはオブジェクトボックスの "unbreakable" プロパティを指定します。true の場合、ボックス内部で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータにとって重要です。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。デフォルト: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**戻り値:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

改行なし このプロパティはオブジェクトボックスの "unbreakable" プロパティを指定します。true の場合、ボックス内部で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータにとって重要です。この要素が指定されていない場合、ボックス内部で改行が発生する可能性があります。デフォルト: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

微分 真の場合、ボックスは微分として機能し（例: \\ud835\\udc51\\ud835\\udc65 を積分子内で使用）、数学的微分に適切な水平間隔を受け取ります。デフォルト: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**戻り値:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

微分 真の場合、ボックスは微分として機能し（例: \\ud835\\udc51\\ud835\\udc65 を積分子内で使用）、数学的微分に適切な水平間隔を受け取ります。デフォルト: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

真の場合、この演算子エミュレータは位置合わせポイントとして機能します。つまり、他の式で指定された位置合わせポイントと揃えることができます。デフォルト: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**戻り値:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

真の場合、この演算子エミュレータは位置合わせポイントとして機能します。つまり、他の式で指定された位置合わせポイントと揃えることができます。デフォルト: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

明示的な改行 ボックスオブジェクトの開始位置で改行があるかどうかを指定し、行がボックスオブジェクトの開始位置で折り返されます。前の行の数式テキストにある演算子の番号を指定し、現在の行の数式テキストの位置合わせポイントとして使用します。可能な値: 1..255 デフォルト: 0（明示的な改行なし）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**戻り値:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

明示的な改行 ボックスオブジェクトの開始位置で改行があるかどうかを指定し、行がボックスオブジェクトの開始位置で折り返されます。前の行の数式テキストにある演算子の番号を指定し、現在の行の数式テキストの位置合わせポイントとして使用します。可能な値: 1..255 デフォルト: 0（明示的な改行なし）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps