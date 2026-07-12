---
title: MathFunction
second_title: Java API リファレンスによる Aspose.Slides for Android
description: 引数の関数を指定します。
type: docs
url: /ja/com.aspose.slides/mathfunction/
---
**継承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

引数の関数を指定します。

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | MathFunction クラスの新しいインスタンスを初期化します。 |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | MathFunction クラスの新しいインスタンスを初期化します。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getName()](#getName--) | 関数名 例として、関数名は sin と cos です |
| [getBase()](#getBase--) | 関数引数 |
| [getChildren()](#getChildren--) | 子要素を取得 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 制御文字プロパティ |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


MathFunction クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


MathFunction クラスの新しいインスタンスを初期化します。

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


関数名 例として、関数名は sin と cos です

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```


**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


関数引数

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


子要素を取得

**戻り値:**
com.aspose.slides.IMathElement[] - [IMathElement](../../com.aspose.slides/imathelement) の配列
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


制御文字プロパティ

**戻り値:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps