---
title: MathNaryOperator
second_title: Aspose.Slides Java API 参考
description: 指定一个 N 元数学对象，例如求和和积分。
type: docs
url: /zh/com.aspose.slides/mathnaryoperator/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathNaryOperator](../../com.aspose.slides/imathnaryoperator), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathNaryOperator extends MathElementBase implements IMathNaryOperator, IHasControlCharacterProperties
```

指定一个 N 元数学对象，例如求和（Summation）和积分（Integral）。它由运算符、基数（或操作数）以及可选的上限和下限组成。N 元运算符的示例包括：求和、并集、交集、积分

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 初始化 MathNaryOperator 类的新实例。 |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)](#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | 初始化 MathNaryOperator 类的新实例。 |
| [MathNaryOperator(char operatorSymbol, IMathElement baseArgument)](#MathNaryOperator-char-com.aspose.slides.IMathElement-) | 初始化 MathNaryOperator 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基数参数 |
| [getSubscript()](#getSubscript--) | 指定下标参数，例如在积分的情况下设置下限 |
| [getSuperscript()](#getSuperscript--) | 指定上标参数，例如在积分的情况下设置上限 |
| [getOperator()](#getOperator--) | N 元运算符字符，例如：'\\u2211'，'\\u222b' |
| [setOperator(char value)](#setOperator-char-) | N 元运算符字符，例如：'\\u2211'，'\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | 限制的位置（下标和上标） |
| [setLimitLocation(int value)](#setLimitLocation-int-) | 限制的位置（下标和上标） |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | 运算符字符垂直增长以匹配其操作数的高度 |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | 运算符字符垂直增长以匹配其操作数的高度 |
| [getHideSubscript()](#getHideSubscript--) | 隐藏下标 |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | 隐藏下标 |
| [getHideSuperscript()](#getHideSuperscript--) | 隐藏上标 |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | 隐藏上标 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit, IMathElement upperLimit)
```

初始化 MathNaryOperator 类的新实例。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i=0"), new MathematicalText("\ud835\udc5b"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | N 元运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基数参数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | 上限 |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit) {#MathNaryOperator-char-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument, IMathElement lowerLimit)
```

初始化 MathNaryOperator 类的新实例。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"), new MathematicalText("i"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | N 元运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基数参数 |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | 下限 |

### MathNaryOperator(char operatorSymbol, IMathElement baseArgument) {#MathNaryOperator-char-com.aspose.slides.IMathElement-}
```
public MathNaryOperator(char operatorSymbol, IMathElement baseArgument)
```

初始化 MathNaryOperator 类的新实例。

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathNaryOperator('\u2211', new MathematicalText("i"));
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| operatorSymbol | char | N 元运算符符号 |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | 基数参数 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基数参数

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement baseArg = naryOperator.getBase();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSubscript() {#getSubscript--}
```
public final IMathElement getSubscript()
```

指定下标参数，例如在积分的情况下设置下限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement subscriptArg = naryOperator.getSubscript();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getSuperscript() {#getSuperscript--}
```
public final IMathElement getSuperscript()
```

指定上标参数，例如在积分的情况下设置上限

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  IMathElement superscriptArg = naryOperator.getSuperscript();
> ```

**返回值：**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperator() {#getOperator--}
```
public final char getOperator()
```

N 元运算符字符，例如：'\\u2211'，'\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**返回值：**
char
### setOperator(char value) {#setOperator-char-}
```
public final void setOperator(char value)
```

N 元运算符字符，例如：'\\u2211'，'\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public final int getLimitLocation()
```

限制的位置（下标和上标）

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**返回值：**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public final void setLimitLocation(int value)
```

限制的位置（下标和上标）

--------------------

> ```
> 示例：
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

运算符字符垂直增长以匹配其操作数的高度

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**返回值：**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

运算符字符垂直增长以匹配其操作数的高度

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public final boolean getHideSubscript()
```

隐藏下标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**返回值：**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public final void setHideSubscript(boolean value)
```

隐藏下标

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public final boolean getHideSuperscript()
```

隐藏上标

--------------------

> ```
> 示例：
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**返回值：**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public final void setHideSuperscript(boolean value)
```

隐藏上标

--------------------

> ```
> 示例:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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