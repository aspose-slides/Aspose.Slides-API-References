---
title: MathRadical
second_title: Aspose.Slides for Android 用 Java API リファレンス
description: 基底と任意の次数からなる根号関数を指定します。
type: docs
url: /ja/com.aspose.slides/mathradical/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

基底と任意の次数からなる根号関数を指定します。根号オブジェクトの例は \\u221a\\ud835\\udc65 です。

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRadical クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getDegree()](#getDegree--) | 次数引数 |
| [getHideDegree()](#getHideDegree--) | Hide degree が true の場合、次数は表示されず、\\u221a\\ud835\\udc65 のようになります |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree が true の場合、次数は表示されず、\\u221a\\ud835\\udc65 のようになります |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | 子要素を取得する |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


MathRadical クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基底 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 次数 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基底引数

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


次数引数

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


Hide degree が true の場合、次数は表示されず、\\u221a\\ud835\\udc65 のようになります

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**戻り値:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


Hide degree が true の場合、次数は表示されず、\\u221a\\ud835\\udc65 のようになります

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
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


子要素を取得する

**戻り値:**
com.aspose.slides.IMathElement[]