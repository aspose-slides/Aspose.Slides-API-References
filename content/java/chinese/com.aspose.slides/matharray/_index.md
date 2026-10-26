---
title: MathArray
second_title: Aspose.Slides for Java API 参考
description: 指定一组垂直排列的方程或任何数学对象
type: docs
url: /zh/com.aspose.slides/matharray/
---
**继承：**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**所有实现的接口：**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

指定一组垂直排列的公式或任何数学对象

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | 创建一个数学数组并将指定的元素放入其中 |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | 创建一个数学数组并将指定的元素放入其中 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArguments()](#getArguments--) | 数组的项目集合 |
| [getBaseJustification()](#getBaseJustification--) | 指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | Maximum Distribution 当为 true 时，数组的间距将扩展到包含元素（页面、列、单元格等）的最大宽度。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Maximum Distribution 当为 true 时，数组的间距将扩展到包含元素（页面、列、单元格等）的最大宽度。 |
| [getObjectDistribution()](#getObjectDistribution--) | Object Distribution 当为 true 时，数组的内容将扩展到数组对象的最大宽度。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Object Distribution 当为 true 时，数组的内容将扩展到数组对象的最大宽度。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 数组元素之间垂直间距的类型。默认值：SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 数组元素之间垂直间距的类型。默认值：SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | 数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时度量单位为半行。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时度量单位为半行。 |
| [getChildren()](#getChildren--) | 获取子元素 |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

创建一个数学数组并将指定的元素放入其中

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | 要放入数组的元素 |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

创建一个数学数组并将指定的元素放入其中

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | 要放入数组的元素 |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

数组的项目集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**返回值:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**返回值:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

Maximum Distribution 当为 true 时，数组的间距将扩展到包含元素（页面、列、单元格等）的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**返回值:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Maximum Distribution 当为 true 时，数组的间距将扩展到包含元素（页面、列、单元格等）的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

Object Distribution 当为 true 时，数组的内容将扩展到数组对象的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**返回值:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Object Distribution 当为 true 时，数组的内容将扩展到数组对象的最大宽度。

--------------------

> ```
> Example:
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

数组元素之间垂直间距的类型。默认值：SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**返回值:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

数组元素之间垂直间距的类型。默认值：SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时度量单位为半行。默认值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**返回值:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用。此时度量单位为点；或在 Multiple 时度量单位为半行。默认值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

获取子元素

**返回值:**
com.aspose.slides.IMathElement[]