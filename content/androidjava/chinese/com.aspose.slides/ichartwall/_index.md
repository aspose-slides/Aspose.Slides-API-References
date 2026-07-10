---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 3d 图表上的墙体。
type: docs
url: /zh/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

表示墙体在 3d 图表上。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getThickness()](#getThickness--) | 返回或设置墙体厚度，作为绘图体积最大维度的百分比。 |
| [setThickness(int value)](#setThickness-int-) | 返回或设置墙体厚度，作为绘图体积最大维度的百分比。 |
| [getFormat()](#getFormat--) | 返回墙体的填充、线条、效果、3d 样式。 |
| [getPictureType()](#getPictureType--) | 返回或设置图片类型。 |
| [setPictureType(int value)](#setPictureType-int-) | 返回或设置图片类型。 |

### getThickness() {#getThickness--}
```
public abstract int getThickness()
```

返回或设置墙体厚度，作为绘图体积最大维度的百分比。读取/写入 int.

**返回:**
int

### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```

返回或设置墙体厚度，作为绘图体积最大维度的百分比。读取/写入 int.

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

返回墙体的填充、线条、效果、3d 样式。只读 [IFormat](../../com.aspose.slides/iformat).

**返回:**
[IFormat](../../com.aspose.slides/iformat)

### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```

返回或设置图片类型。读取/写入 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**返回:**
int

### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```

返回或设置图片类型。读取/写入 [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |