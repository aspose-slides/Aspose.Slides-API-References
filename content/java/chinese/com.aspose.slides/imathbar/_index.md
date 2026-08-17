---
title: IMathBar
second_title: Aspose.Slides for Java API 参考
description: 指定 bar 函数，由基础参数和上划线或下划线组成
type: docs
url: /zh/com.aspose.slides/imathbar/
---
**所有实现的接口:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

指定 bar 函数，由基础参数和上划线或下划线组成

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基础参数 |
| [getPosition()](#getPosition--) | Bar线的位置。 |
| [setPosition(int value)](#setPosition-int-) | Bar线的位置。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基础参数

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**返回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Bar线的位置。默认：顶部

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**返回值:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Bar线的位置。默认：顶部

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |