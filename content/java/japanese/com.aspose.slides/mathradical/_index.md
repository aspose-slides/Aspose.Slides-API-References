---
title: MathRadical
second_title: Aspose.Slides for Java API リファレンス
description: 基底と任意の指数からなる根号関数を指定します。
type: docs
url: /ja/com.aspose.slides/mathradical/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

基底と任意の指数からなる根号関数を指定します。根号オブジェクトの例は \\u221a\\ud835\\udc65 です。

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## コンストラクタ

| Constructor | Description |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathRadical クラスの新しいインスタンスを初期化します。 |
## メソッド

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 基底引数 |
| [getDegree()](#getDegree--) | 指数引数 |
| [getHideDegree()](#getHideDegree--) | Hide degree が true の場合、指数は表示されません（例: \\u221a\\ud835\\udc65） |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree が true の場合、指数は表示されません（例: \\u221a\\ud835\\udc65） |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
| [getChildren()](#getChildren--) | 子要素を取得 |
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
| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基底 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 指数 |

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


指数引数

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


Hide degree が true の場合、指数は表示されません（例: \\u221a\\ud835\\udc65）

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


Hide degree が true の場合、指数は表示されません（例: \\u221a\\ud835\\udc65）

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**パラメーター:**
| Parameter | Type | Description |
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


子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[]