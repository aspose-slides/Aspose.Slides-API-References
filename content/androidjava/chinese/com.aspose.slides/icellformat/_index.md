---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table cell.
type: docs
url: /zh/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

表示表格单元格的格式。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回单元格填充属性对象。 |
| [getBorderLeft()](#getBorderLeft--) | 返回左边框线属性对象。 |
| [getBorderTop()](#getBorderTop--) | 返回上边框线属性对象。 |
| [getBorderRight()](#getBorderRight--) | 返回右边框线属性对象。 |
| [getBorderBottom()](#getBorderBottom--) | 返回下边框线属性对象。 |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | 返回左上到右下对角线属性对象。 |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | 返回左下到右上对角线属性对象。 |
| [getTransparency()](#getTransparency--) | 获取或设置填充颜色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 获取或设置填充颜色的透明度。 |
| [getEffective()](#getEffective--) | 获取在继承和表格样式应用后的有效单元格格式属性。 |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

返回单元格填充属性对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

返回左边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

返回上边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

返回右边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

返回下边框线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```

返回左上到右下对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```

返回左下到右上对角线属性对象。只读 [ILineFormat](../../com.aspose.slides/ilineformat)。

**返回:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

获取或设置填充颜色的透明度。读写  float 。

**返回:**  
float

### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

获取或设置填充颜色的透明度。读写  float 。

**参数:**  
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

获取在继承和表格样式应用后的有效单元格格式属性。

**返回:**  
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - 一个 [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).