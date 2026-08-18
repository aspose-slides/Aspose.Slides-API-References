---
title: MathNaryOperator
second_title: Aspose.Slides の Java API リファレンス
description: 総和や積分などの N 変数数学オブジェクトを指定します。
type: docs
url: /ja/com.aspose.slides/mathnaryoperator/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

N-ary の数学オブジェクト（総和や積分など）を指定します。演算子、基底（またはオペランド）およびオプションの上限と下限から構成されます。N-ary 演算子の例: 総和、合併、交差、積分

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | MathNaryOperator クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getSubscript()](#getSubscript--) | 下付き引数を指定します。たとえば積分の場合、下限を設定します。 |
| [getSuperscript()](#getSuperscript--) | 上付き引数を指定します。たとえば積分の場合、上限を設定します。 |
| [getOperator()](#getOperator--) | Nary 演算子文字 例: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Nary 演算子文字 例: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 限界（下付きと上付き）の位置 |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 限界（下付きと上付き）の位置 |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 演算子文字はオペランドの高さに合わせて垂直方向に伸長します |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 演算子文字はオペランドの高さに合わせて垂直方向に伸長します |
| [getHideSubscript()](#getHideSubscript--) | 下付き文字を非表示 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 下付き文字を非表示 |
| [getHideSuperscript()](#getHideSuperscript--) | 上付き文字を非表示 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 上付き文字を非表示 |
| [getChildren()](#getChildren--) | 子要素を取得 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```


MathNaryOperator クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | Nary 演算子シンボル |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ベース引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```


MathNaryOperator クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | Nary 演算子シンボル |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ベース引数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```


MathNaryOperator クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| operatorSymbol | char | Nary 演算子シンボル |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | ベース引数 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


ベース引数

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```


下付き引数を指定します。たとえば積分の場合、下限を設定します。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```


上付き引数を指定します。たとえば積分の場合、上限を設定します。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```


Nary 演算子文字 例: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**戻り値:**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```


Nary 演算子文字 例: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```


限界（下付きと上付き）の位置

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**戻り値:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```


限界（下付きと上付き）の位置

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```


演算子文字はオペランドの高さに合わせて垂直方向に伸長します

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**戻り値:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```


演算子文字はオペランドの高さに合わせて垂直方向に伸長します

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```


下付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**戻り値:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```


下付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```


上付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**戻り値:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```


上付き文字を非表示

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

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