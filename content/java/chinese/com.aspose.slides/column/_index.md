---
title: Column
second_title: Aspose.Slides Java API 参考
description: 表示表格中的一列。
type: docs
url: /zh/com.aspose.slides/column/
---
**继承:**
java.lang.Object, [com.aspose.slides.CellCollection](../../com.aspose.slides/cellcollection)

**所有实现的接口:**
[com.aspose.slides.IColumn](../../com.aspose.slides/icolumn)
```
public final class Column extends CellCollection implements IColumn
```

表示表格中的一列。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getWidth()](#getWidth--) | 返回或设置列的宽度。 |
| [setWidth(double value)](#setWidth-double-) | 返回或设置列的宽度。 |
| [setTextFormat(IPortionFormat source)](#setTextFormat-com.aspose.slides.IPortionFormat-) | 将已定义的部分格式属性设置到所有列单元格的部分。 |
| [setTextFormat(IParagraphFormat source)](#setTextFormat-com.aspose.slides.IParagraphFormat-) | 将已定义的段落格式属性设置到所有列单元格的段落。 |
| [setTextFormat(ITextFrameFormat source)](#setTextFormat-com.aspose.slides.ITextFrameFormat-) | 将已定义的文本框架格式属性设置到所有列单元格的文本框架。 |
| [getColumnFormat()](#getColumnFormat--) | 返回包含此列格式属性的 ColumnFormat 对象。 |
### getWidth() {#getWidth--}
```
public final double getWidth()
```


返回或设置列的宽度。读/写 double.

**返回：**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


返回或设置列的宽度。读/写 double.

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | double |  |

### setTextFormat(IPortionFormat source) {#setTextFormat-com.aspose.slides.IPortionFormat-}
```
public final void setTextFormat(IPortionFormat source)
```


将已定义的部分格式属性设置到所有列单元格的部分。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IPortionFormat](../../com.aspose.slides/iportionformat) | IPortionFormat 对象已设置必要属性。 |

### setTextFormat(IParagraphFormat source) {#setTextFormat-com.aspose.slides.IParagraphFormat-}
```
public final void setTextFormat(IParagraphFormat source)
```


将已定义的段落格式属性设置到所有列单元格的段落。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [IParagraphFormat](../../com.aspose.slides/iparagraphformat) | IParagraphFormat 对象已设置必要属性。 |

### setTextFormat(ITextFrameFormat source) {#setTextFormat-com.aspose.slides.ITextFrameFormat-}
```
public final void setTextFormat(ITextFrameFormat source)
```


将已定义的文本框架格式属性设置到所有列单元格的文本框架。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [ITextFrameFormat](../../com.aspose.slides/itextframeformat) | ITextFrameFormat 对象已设置必要属性。 |

### getColumnFormat() {#getColumnFormat--}
```
public final IColumnFormat getColumnFormat()
```


返回包含此列格式属性的 ColumnFormat 对象。只读 [IColumnFormat](../../com.aspose.slides/icolumnformat)。

**返回：**
[IColumnFormat](../../com.aspose.slides/icolumnformat)