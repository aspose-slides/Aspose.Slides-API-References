---
title: MathBar
second_title: Aspose.Slides Java API 参考
description: 指定由基参数和上划线或下划线组成的栏函数
type: docs
url: /zh/com.aspose.slides/mathbar/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

指定栏函数，由基参数和上划线或下划线组成

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | 使用上划线（顶部位置）初始化 MathBar |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | 使用指定位置初始化 MathBar |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getPosition()](#getPosition--) | 栏线的位置。 |
| [setPosition(int value)](#setPosition-int-) | 栏线的位置。 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

使用上划线（顶部位置）初始化 MathBar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用于栏的基元素 |
### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

使用指定位置初始化 MathBar

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 应用于栏的基元素 |
| position | int | 栏线的位置。 |
### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基参数

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

栏线的位置。默认：顶部

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**返回值：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

栏线的位置。默认：顶部

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回值：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回值：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps