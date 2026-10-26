---
title: MathBox
second_title: Aspose.Slides for Java API 参考
description: 指定数学元素的逻辑盒装包装。
type: docs
url: /zh/com.aspose.slides/mathbox/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

指定数学元素的逻辑盒装（包装）。例如，盒装对象可以作为带或不带对齐点的运算符模拟器，作为换行点，或被分组以防止在其中换行。例如，"==" 运算符应被盒装以防止换行。

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | 使用指定的元素作为参数初始化 MathBox |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBase()](#getBase--) | 基础参数 |
| [getOperatorEmulator()](#getOperatorEmulator--) | 运算符模拟器。 |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | 运算符模拟器。 |
| [getNoBreak()](#getNoBreak--) | 不换行 此属性指定对象盒的“不可换行”属性。 |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | 不换行 此属性指定对象盒的“不可换行”属性。 |
| [getDifferential()](#getDifferential--) | 微分 当为 true 时，盒子充当微分符号（例如 integrand 中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距。 |
| [setDifferential(boolean value)](#setDifferential-boolean-) | 微分 当为 true 时，盒子充当微分符号（例如 integrand 中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距。 |
| [getAlignmentPoint()](#getAlignmentPoint--) | 当为 true 时，此运算符模拟器充当对齐点；即其他方程中的指定对齐点可与之对齐。 |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | 当为 true 时，此运算符模拟器充当对齐点；即其他方程中的指定对齐点可与之对齐。 |
| [getExplicitBreak()](#getExplicitBreak--) | 显式换行 指定盒对象起始处是否有换行，从而在盒对象起始处换行。 |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | 显式换行 指定盒对象起始处是否有换行，从而在盒对象起始处换行。 |
| [getChildren()](#getChildren--) | 获取子元素 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | 控制字符属性 |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

使用指定的元素作为参数初始化 MathBox

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要应用盒子的基础元素。可以为 null。 |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

基础参数

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**返回：**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

运算符模拟器。当为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点并可与其他运算符对齐。运算符模拟器常用于一个或多个字形组合形成运算符的情况，如 '=='。默认值：false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**返回：**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

运算符模拟器。当为 true 时，盒子及其内容表现为单个运算符并继承运算符的属性。这意味着，例如，该字符可以作为换行点并可与其他运算符对齐。运算符模拟器常用于一个或多个字形组合形成运算符的情况，如 '=='。默认值：false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

不换行 此属性指定对象盒的“不可换行”属性。当为 true 时，盒内不能出现换行。这对由多个二元运算符组成的运算符模拟器很重要。如果未指定此元素，盒内可以出现换行。默认：true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**返回：**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

不换行 此属性指定对象盒的“不可换行”属性。当为 true 时，盒内不能出现换行。这对由多个二元运算符组成的运算符模拟器很重要。如果未指定此元素，盒内可以出现换行。默认：true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

微分 当为 true 时，盒子充当微分符号（例如 integrand 中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距。默认：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**返回：**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

微分 当为 true 时，盒子充当微分符号（例如 integrand 中的 \\ud835\\udc51\\ud835\\udc65），并获得适当的水平间距。默认：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

当为 true 时，此运算符模拟器充当对齐点；即其他方程中的指定对齐点可与之对齐。默认：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**返回：**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

当为 true 时，此运算符模拟器充当对齐点；即其他方程中的指定对齐点可与之对齐。默认：false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

显式换行 指定盒对象起始处是否有换行，从而在盒对象起始处换行。指定前一行数学文本中运算符的编号，作为当前行数学文本的对齐点，可能的值：1..255 默认：0（无显式换行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**返回：**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

显式换行 指定盒对象起始处是否有换行，从而在盒对象起始处换行。指定前一行数学文本中运算符的编号，作为当前行数学文本的对齐点，可能的值：1..255 默认：0（无显式换行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回：**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

控制字符属性

**返回：**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps