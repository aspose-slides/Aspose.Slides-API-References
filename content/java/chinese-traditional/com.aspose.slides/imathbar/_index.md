---
title: IMathBar
second_title: Aspose.Slides 的 Java API 參考
description: 指定由基礎參數與上標或下標組成的 bar 函式
type: docs
url: /zh-hant/com.aspose.slides/imathbar/
---
**所有已实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBar extends IMathElement
```

指定 bar 函式，由基礎參數與上標或下標組成

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基礎參數 |
| [getPosition()](#getPosition--) | 條形線的位置。 |
| [setPosition(int value)](#setPosition-int-) | 條形線的位置。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


基礎參數

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```

**傳回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


條形線的位置。預設值：上方

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**傳回值：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


條形線的位置。預設值：上方

--------------------

> ```
> Example:
>  
>  IMathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |