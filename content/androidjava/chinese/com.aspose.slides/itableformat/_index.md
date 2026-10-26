---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API 参考
description: 表示表格的格式。
type: docs
url: /zh/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

表示表格的格式。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 返回表填充属性对象。 |
| [getTransparency()](#getTransparency--) | 获取或设置填充颜色的透明度。 |
| [setTransparency(float value)](#setTransparency-float-) | 获取或设置填充颜色的透明度。 |
| [getEffective()](#getEffective--) | 获取有效的表格格式属性，已应用继承和表格样式。 |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


返回表填充属性对象。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


获取或设置填充颜色的透明度。读/写  float 。

**返回值:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


获取或设置填充颜色的透明度。读/写  float 。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


获取有效的表格格式属性，已应用继承和表格样式。

**返回值:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - 一个 [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).