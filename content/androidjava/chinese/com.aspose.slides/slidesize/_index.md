---
title: SlideSize
second_title: Aspose.Slides for Android via Java API 参考
description: 表示幻灯片的大小和方向。
type: docs
url: /zh/com.aspose.slides/slidesize/
---
**继承：**
java.lang.Object, com.aspose.slides.DomObject

**所有实现的接口：**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

表示幻灯片的大小和方向。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getSize()](#getSize--) | 获取幻灯片的尺寸（单位为点）。 |
| [getType()](#getType--) | 获取幻灯片大小类型。 |
| [getOrientation()](#getOrientation--) | 获取或设置幻灯片方向。 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置幻灯片方向。 |
| [setSize(int type, int scaleType)](#setSize-int-int-) | 通过类型设置幻灯片大小并缩放现有内容。 |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | 显式设置幻灯片尺寸并缩放现有内容。 |

### getSize() {#getSize--}
```
public final SizeF getSize()
```

获取幻灯片的尺寸（单位为点）。

--------------------

为新值赋值会将 \#getType.getType 属性重置为 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，并设置 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**返回值：**
[SizeF](../../com.aspose.slides.android/sizef)

### getType() {#getType--}
```
public final int getType()
```

获取幻灯片大小类型。

--------------------

将任何非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值赋给它，会根据预定义尺寸调整 \#getSize.getSize，同时保留当前的 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。

**返回值：**
int

### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

获取或设置幻灯片方向。

--------------------

更改此值会交换幻灯片的宽度和高度。

**返回值：**
int

### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
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
public final void setSize(int type, int scaleType)
```

通过类型设置幻灯片大小并缩放现有内容。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 要应用的预定义幻灯片大小。 |
| scaleType | int | 要使用的内容缩放模式。 |

--------------------

将任何非 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) 的值赋给它，会根据所选类型调整 \#getSize.getSize，同时保留 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

显式设置幻灯片尺寸并缩放现有内容。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| width | float | 新的幻灯片宽度（单位为点）。 |
| height | float | 新的幻灯片高度（单位为点）。 |
| scaleType | int | 要使用的内容缩放模式。 |

--------------------

这会将 \#getType.getType 属性重置为 [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom)，并设置 \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int)。 |