---
title: MathRadical
second_title: Aspose.Slides for Java API 参考
description: 指定由基数和可选指数组成的根函数。
type: docs
url: /zh/com.aspose.slides/mathradical/
---
**继承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**实现的所有接口:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

指定根函数，由基数和可选的指数组成。根对象的示例为 \\u221a\\ud835\\udc65。

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 初始化 MathRadical 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基参数 |
| [getDegree()](#getDegree--) | 指数参数 |
| [getHideDegree()](#getHideDegree--) | 隐藏指数。当为 true 时，指数不显示，如 \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | 隐藏指数。当为 true 时，指数不显示，如 \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
| [getChildren()](#getChildren--) | 获取子元素 |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```


初始化 MathRadical 类的新实例。

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基数 |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | 指数 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


基数参数

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**返回:**
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```


指数参数

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**返回:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```


隐藏指数。当为 true 时，指数不显示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**返回:**
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```


隐藏指数。当为 true 时，指数不显示，如 \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


控制字符属性

**返回:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


获取子元素

**返回:**
com.aspose.slides.IMathElement[]