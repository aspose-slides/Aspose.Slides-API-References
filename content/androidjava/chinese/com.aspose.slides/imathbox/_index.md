---
title: IMathBox
second_title: Aspose.Slides for Android via Java API 参考文档
description: 指定数学元素的逻辑装箱包装。
type: docs
url: /zh/com.aspose.slides/imathbox/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

指定数学元素的逻辑装箱（打包）。例如，装箱对象可以作为带或不带对齐点的运算符仿真器，可以作为换行点，或被分组以防止在内部出现换行。例如，应该对 "==" 运算符进行装箱以防止换行。

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break. |
| [getDifferential()](#getDifferential--) | Differential. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential. |
| [getAlignmentPoint()](#getAlignmentPoint--) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Base argument

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
>  ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
>  ```

**Returns:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Operator Emulator. When true, the box and its contents behave as a single operator and inherit the properties of an operator. This means, for example, that the character can serve as a point for a line break and can be aligned to other operators. Operator Emulators are often used when one or more glyphs combine to form an operator, such as '=='. Default value: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
>  ```

**Returns:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

No break. This property specifies the "unbreakable" property on the object box. When true, no line breaks can occur within the box. This can be important for operator emulators that consist of more than one binary operator. When this element is not specified, breaks can occur inside box. Default: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

微分。当值为 true 时，盒子充当微分（例如，\\ud835\\udc51\\ud835\\udc65 在被积中），并获得数学微分所需的水平间距。默认值：false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
>  ```

**返回：**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Differential. When true, the box acts as a differential (e.g., \\ud835\\udc51\\ud835\\udc65 in an integrand), and receives the appropriate horizontal spacing for the mathematical differential. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public abstract boolean getAlignmentPoint()
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
>  ```

**Returns:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

When true, this operator emulator serves as an alignment point; that is, designated alignment points in other equations can be aligned with it. Default: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
>  ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public abstract byte getExplicitBreak()
```

Explicit break specifies whether there is a line break at the start of the Box object, such that the line wraps at the start of the box object. Specifies the number of the operator on the previous line of mathematical text which shall be used as the alignment point for the current line of mathematical text possible values: 1..255 Default: 0 (no explicit break)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
>  ```

**Returns:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)


显式换行指定 Box 对象起始位置是否存在换行，从而使行在 Box 对象的起始处换行。它指定前一行数学文本中运算符的编号，该编号将用作当前行数学文本的对齐点。可能的取值范围：1..255 默认值：0（无显式换行）

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |