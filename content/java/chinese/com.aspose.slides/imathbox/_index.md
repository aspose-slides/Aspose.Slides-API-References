---
title: IMathBox
second_title: Aspose.Slides for Java API 参考
description: 指定数学元素的逻辑打盒包装。
type: docs
url: /zh/com.aspose.slides/imathbox/
---
**所有实现的接口:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

指定数学元素的逻辑包装（打盒）。例如，打盒对象可以充当带或不带对齐点的运算符仿真器，充当换行点，或被分组以不允许在内部换行。例如，"==" 运算符应被打盒以防止换行。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## 方法

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | 基础参数 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 运算符仿真器。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 运算符仿真器。 |
| [getNoBreak()](#getNoBreak--) | 不换行。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 不换行。 |
| [getDifferential()](#getDifferential--) | 微分。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 当为 true 时，此运算符仿真器充当对齐点；即其他等式中指定的对齐点可以与之对齐。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 当为 true 时，此运算符仿真器充当对齐点；即其他等式中指定的对齐点可以与之对齐。 |
| [getExplicitBreak()](#getExplicitBreak--) | 显式换行指定在 Box 对象的起始是否有换行，从而在盒子对象起始处换行。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 显式换行指定在 Box 对象的起始是否有换行，从而在盒子对象起始处换行。 |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

基础参数

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**返回值:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

运算符仿真器。当为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点并可以与其他运算符对齐。运算符仿真器通常在一个或多个字形组合成运算符（如 “==”）时使用。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**返回值:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

运算符仿真器。当为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点并可以与其他运算符对齐。运算符仿真器通常在一个或多个字形组合成运算符（如 “==”）时使用。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

不换行。此属性指定对象盒子的“不可换行”属性。当为 true 时，盒子内部不能出现换行。这在由多个二元运算符组成的运算符仿真器中可能很重要。如果未指定此元素，盒子内部可以出现换行。默认值：true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**返回值:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

不换行。此属性指定对象盒子的“不可换行”属性。当为 true 时，盒子内部不能出现换行。这在由多个二元运算符组成的运算符仿真器中可能很重要。如果未指定此元素，盒子内部可以出现换行。默认值：true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

微分。当为 true 时，盒子充当微分（例如，在被积函数中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距以符合数学微分的排版。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**返回值:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

微分。当为 true 时，盒子充当微分（例如，在被积函数中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距以符合数学微分的排版。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

当为 true 时，此运算符仿真器充当对齐点；即其他等式中指定的对齐点可以与之对齐。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**返回值:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

当为 true 时，此运算符仿真器充当对齐点；即其他等式中指定的对齐点可以与之对齐。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

显式换行指定在 Box 对象的起始是否有换行，从而在盒子对象起始处换行。指定前一行数学文本中运算符的编号，用作当前行数学文本的对齐点。可能的取值：1..255 默认值：0（无显式换行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**返回值:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

显式换行指定在 Box 对象的起始是否有换行，从而在盒子对象起始处换行。指定前一行数学文本中运算符的编号，用作当前行数学文本的对齐点。可能的取值：1..255 默认值：0（无显式换行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**参数:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |