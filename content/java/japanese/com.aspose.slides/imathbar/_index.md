---
title: IMathBar
second_title: Aspose.Slides for Java API リファレンス
description: ベース引数と上部バーまたは下部バーからなるバー関数を指定します
type: docs
url: /ja/com.aspose.slides/imathbar/
---
**すべての実装インターフェース:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

ベース引数と上部バーまたは下部バーからなるバー関数を指定します

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
```
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getBase()](#getBase--) | ベース引数 |
| [getPosition()](#getPosition--) | バーラインの位置。 |
| [setPosition(int value)](#setPosition-int-) | バーラインの位置。 |
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


バーラインの位置。 デフォルト: Top

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


バーラインの位置。 デフォルト: Top

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |