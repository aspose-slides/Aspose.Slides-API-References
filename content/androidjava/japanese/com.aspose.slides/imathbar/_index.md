---
title: IMathBar
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: ベース引数とオーバーバーまたはアンダーバーからなるバー関数を指定します
type: docs
url: /ja/com.aspose.slides/imathbar/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

ベース引数とオーバーバーまたはアンダーバーからなるバー関数を指定します

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getPosition()](#getPosition--) | バー線の位置。 |
| [setPosition(int value)](#setPosition-int-) | バー線の位置。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


ベース引数

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**戻り値:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


バー線の位置。デフォルト: 上

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


バー線の位置。デフォルト: 上

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |