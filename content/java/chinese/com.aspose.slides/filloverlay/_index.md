---
title: FillOverlay
second_title: Aspose.Slides Java API 参考
description: 表示 Fill Overlay 效果。
type: docs
url: /zh/com.aspose.slides/filloverlay/
---
**继承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**全部实现的接口:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

表示一个 Fill Overlay 效果。Fill Overlay 可用于为对象指定额外的填充并将两种填充混合在一起。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | 填充格式。 |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | 获取已应用继承的有效 Fill Overlay 效果数据。 |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 确定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等于当前的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |
| [hashCode()](#hashCode--) | 用作特定类型的哈希函数。 |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

填充格式。只读 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回值:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. 读写 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**返回值:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. 读写 [FillBlendMode](../../com.aspose.slides/fillblendmode)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

获取已应用继承的有效 Fill Overlay 效果数据。

**返回值:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - 一个 [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)。

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。只读 long。

**返回值:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

确定指定的 [FillOverlay](../../com.aspose.slides/filloverlay) 是否等于当前的 [FillOverlay](../../com.aspose.slides/filloverlay)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的 [FillOverlay](../../com.aspose.slides/filloverlay)。 |

**返回值:**
boolean - 如果对象相等则为 true；否则为 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

用作特定类型的哈希函数。

**返回值:**
int - 当前对象的哈希码。