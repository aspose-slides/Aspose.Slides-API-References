---
title: ISlideSize
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the size and orientation of a slide.
type: docs
url: /zh/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

表示幻灯片的大小和方向。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取幻灯片的尺寸（单位：点）。 |
| [getType()](#getType--) | 获取幻灯片尺寸类型。 |
| [getOrientation()](#getOrientation--) | 获取或设置幻灯片方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置幻灯片方向。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 按类型设置幻灯片尺寸并缩放现有内容。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 显式设置幻灯片尺寸并缩放现有内容。 |
### getSize() {#getSize--}
```
public abstract SizeF getSize()
```

获取幻灯片的尺寸（单位：点）。

--------------------

为属性赋新值会将 \#getType.getType 属性重置为 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，并将 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 设置为相应值。

**返回：**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public abstract int getType()
```

获取幻灯片尺寸类型。

--------------------

赋值任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值会根据预定义尺寸调整 \#getSize.getSize，同时保留当前的 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**返回：**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

获取或设置幻灯片方向。

--------------------

更改此值会交换幻灯片的宽度和高度。

**返回：**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

获取或设置幻灯片方向。

--------------------

更改此值会交换幻灯片的宽度和高度。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

按类型设置幻灯片尺寸并缩放现有内容。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要应用的预定义幻灯片尺寸。 |
| scaleType | int | 要使用的内容缩放模式。 |

--------------------

赋值任意非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值会根据所选类型调整 \#getSize.getSize，同时保留 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

显式设置幻灯片尺寸并缩放现有内容。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 新的幻灯片宽度，单位：点。 |
| height | float | 新的幻灯片高度，单位：点。 |
| scaleType | int | 要使用的内容缩放模式。 |

--------------------

这会将 \#getType.getType 属性重置为 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，并将 \{\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) 设置为相应值。