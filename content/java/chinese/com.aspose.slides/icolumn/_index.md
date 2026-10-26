---
title: IColumn
second_title: Aspose.Slides for Java API 参考
description: 表示表格中的一列。
type: docs
url: /zh/com.aspose.slides/icolumn/
---
**所有已实现的接口：**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

表示表格中的一列。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 返回或设置列的宽度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或设置列的宽度。 |
| [getColumnFormat()](#getColumnFormat--) | 返回包含此列格式属性的 ColumnFormat 对象。 |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

返回或设置列的宽度。读/写 double。

**返回:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

返回或设置列的宽度。读/写 double。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |
### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```

返回包含此列格式属性的 ColumnFormat 对象。只读 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**返回:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)