---
title: IMathArray
second_title: Aspose.Slides for Java API 参考
description: 指定一个垂直的方程或任意数学对象数组
type: docs
url: /zh/com.aspose.slides/imatharray/
---
**所有实现的接口：**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

指定一个垂直的方程或任意数学对象数组

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArguments()](#getArguments--) | 数组的项目集合 |
| [getBaseJustification()](#getBaseJustification--) | 指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。 |
| [setBaseJustification(int value)](#setBaseJustification-int-) | 指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。 |
| [getMaximumDistribution()](#getMaximumDistribution--) | 最大分布。当为 true 时，数组的间距会扩展到包含元素（页面、列、单元格等）的最大宽度。 |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | 最大分布。当为 true 时，数组的间距会扩展到包含元素（页面、列、单元格等）的最大宽度。 |
| [getObjectDistribution()](#getObjectDistribution--) | 对象分布。当为 true 时，数组的内容会扩展到数组对象的最大宽度。 |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | 对象分布。当为 true 时，数组的内容会扩展到数组对象的最大宽度。 |
| [getRowSpacingRule()](#getRowSpacingRule--) | 数组元素之间的垂直间距类型 |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | 数组元素之间的垂直间距类型 |
| [getRowSpacing()](#getRowSpacing--) | 数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用；若为 Exact，则计量单位为点；若为 Multiple，则计量单位为半行。 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | 数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用；若为 Exact，则计量单位为点；若为 Multiple，则计量单位为半行。 |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

数组的项目集合

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**返回值：**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**返回值：**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

指定数组相对于周围文本的对齐方式。数组外部的文本可以与数组对象的底部、顶部或中心对齐。默认值：Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

最大分布。当为 true 时，数组的间距会扩展到包含元素（页面、列、单元格等）的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**返回值：**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

最大分布。当为 true 时，数组的间距会扩展到包含元素（页面、列、单元格等）的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

对象分布。当为 true 时，数组的内容会扩展到数组对象的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**返回值：**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

对象分布。当为 true 时，数组的内容会扩展到数组对象的最大宽度。

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

数组元素之间的垂直间距类型

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**返回值：**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

数组元素之间的垂直间距类型

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用；若为 Exact，则计量单位为点；若为 Multiple，则计量单位为半行。默认值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**返回值：**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

数组行之间的间距。仅在 RowSpacingRule 设置为 3 时使用；若为 Exact，则计量单位为点；若为 Multiple，则计量单位为半行。默认值：0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |