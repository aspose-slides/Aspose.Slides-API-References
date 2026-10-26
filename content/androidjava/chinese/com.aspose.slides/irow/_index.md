---
title: IRow
second_title: Aspose.Slides for Android via Java API 参考
description: 表示表格中的一行。
type: docs
url: /zh/com.aspose.slides/irow/
---
**所有已实现的接口:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

表示表格中的一行。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight()](#getHeight--) | 返回行的高度。 |
| [getMinimalHeight()](#getMinimalHeight--) | 返回或设置行的最小可能高度。 |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | 返回或设置行的最小可能高度。 |
| [getRowFormat()](#getRowFormat--) | 返回包含此行格式属性的 RowFormat 对象。 |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

返回行的高度。只读 double。

**返回：**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

返回或设置行的最小可能高度。读/写 double。

**返回：**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

返回或设置行的最小可能高度。读/写 double。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

返回包含此行格式属性的 RowFormat 对象。只读 [IRowFormat](../../com.aspose.slides/irowformat)。

**返回：**
[IRowFormat](../../com.aspose.slides/irowformat)