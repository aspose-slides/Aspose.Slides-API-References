---
title: IMathBox
second_title: Aspose.Slides for Android 向け Java API リファレンス
description: 数学要素の論理的なボックス化（パッケージ化）を指定します。
type: docs
url: /ja/com.aspose.slides/imathbox/
---
**実装されているすべてのインターフェイス：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

数学要素の論理的なボックス化（パッケージ化）を指定します。例えば、ボックス化されたオブジェクトは、整列ポイントの有無にかかわらず演算子エミュレータとして機能したり、改行ポイントとして機能したり、改行を許さないようにグループ化されたりします。例として、"==" 演算子は改行を防ぐためにボックス化すべきです。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 演算子エミュレータ。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 演算子エミュレータ。 |
| [getNoBreak()](#getNoBreak--) | 改行なし。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 改行なし。 |
| [getDifferential()](#getDifferential--) | 微分。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。 |
| [getExplicitBreak()](#getExplicitBreak--) | 明示的な改行は、Box オブジェクトの先頭に改行があるかどうかを指定します。これにより、行は Box オブジェクトの先頭で折り返されます。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 明示的な改行は、Box オブジェクトの先頭に改行があるかどうかを指定します。これにより、行は Box オブジェクトの先頭で折り返されます。 |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

ベース引数

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

演算子エミュレータ。true の場合、ボックスとその内容は単一の演算子として振る舞い、演算子のプロパティを継承します。つまり、文字が改行ポイントとして機能したり、他の演算子と整列できたりします。演算子エミュレータは、'==' のように複数のグリフが結合して演算子になる場合によく使用されます。既定値: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**戻り値:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

演算子エミュレータ。true の場合、ボックスとその内容は単一の演算子として振る舞い、演算子のプロパティを継承します。つまり、文字が改行ポイントとして機能したり、他の演算子と整列できたりします。演算子エミュレータは、'==' のように複数のグリフが結合して演算子になる場合によく使用されます。既定値: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

改行なし。このプロパティはオブジェクトボックスの「改行不可」属性を指定します。true の場合、ボックス内で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータに重要です。この要素が指定されない場合、ボックス内で改行が発生する可能性があります。既定値: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**戻り値:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

改行なし。このプロパティはオブジェクトボックスの「改行不可」属性を指定します。true の場合、ボックス内で改行は発生しません。これは、複数の二項演算子からなる演算子エミュレータに重要です。この要素が指定されない場合、ボックス内で改行が発生する可能性があります。既定値: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

微分。true の場合、ボックスは微分記号として機能し（例: \\ud835\\udc51\\ud835\\udc65 が積分項に現れる場合）、数学的微分に適した水平間隔が付与されます。既定値: false

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
public abstract void setDifferential(boolean value)
```

微分。true の場合、ボックスは微分記号として機能し（例: \\ud835\\udc51\\ud835\\udc65 が積分項に現れる場合）、数学的微分に適した水平間隔が付与されます。既定値: false

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
public abstract boolean getAlignmentPoint()
```

true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。既定値: false

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
public abstract void setAlignmentPoint(boolean value)
```

true の場合、この演算子エミュレータは整列ポイントとして機能します。つまり、他の式で指定された整列ポイントと合わせることができます。既定値: false

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
public abstract byte getExplicitBreak()
```

明示的な改行は、Box オブジェクトの先頭に改行があるかどうかを指定します。これにより、行は Box オブジェクトの先頭で折り返されます。前行の演算子番号を指定し、現在の行の整列ポイントとして使用します。可能な値: 1..255 既定値: 0（明示的な改行なし）

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
public abstract void setExplicitBreak(byte value)
```

明示的な改行は、Box オブジェクトの先頭に改行があるかどうかを指定します。これにより、行は Box オブジェクトの先頭で折り返されます。前行の演算子番号を指定し、現在の行の整列ポイントとして使用します。可能な値: 1..255 既定値: 0（明示的な改行なし）

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