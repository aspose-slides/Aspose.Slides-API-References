---
title: MathArray
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 指定一个垂直排列的方程或任何数学对象数组
type: docs
url: /zh/com.aspose.slides/matharray/
---
**继承:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

指定一个垂直排列的方程或任何数学对象数组

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Creates a mathematical array and places the specified element in it |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Creates a mathematical array and places specified elements in it |
## Methods

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | The set of items of the array |
| [getBaseJustification()](#getBaseJustification--) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.). |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution When true, the contents of the array are spaced to the maximum width of the array object. |
| [getRowSpacingRule()](#getRowSpacingRule--) | The type of vertical spacing between array elements Default: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | The type of vertical spacing between array elements Default: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. |
| [getChildren()](#getChildren--) | Get children elements |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Creates a mathematical array and places the specified element in it

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | The element to place in the array |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Creates a mathematical array and places specified elements in it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Elements to place in the array |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

The set of items of the array

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Specifies alignment of the array relative to surrounding text Text outside of the array can be aligned with the bottom, top, or center of a array object. Default value: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maximum Distribution When true, the array is spaced to the maximum width of the containing element(page, column, cell, etc.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Object Distribution When true, the contents of the array are spaced to the maximum width of the array object.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

对象分布：当为 true 时，数组的内容会按数组对象的最大宽度进行间距分配。

--------------------

> ```
> 示例：
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

The type of vertical spacing between array elements Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Returns:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

The type of vertical spacing between array elements Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

The type of vertical spacing between array elements Default: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final void setRowSpacing(long value)
```

Spacing between rows of an array It is used only when RowSpacingRule is set to 3 Exactly in which case the unit of measure is points or Multiple in which case the unit of measure is half-lines. Default: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()

获取子元素

**返回:**
com.aspose.slides.IMathElement[]