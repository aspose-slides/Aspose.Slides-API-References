---
title: IFillOverlay
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一种填充覆盖效果。
type: docs
url: /zh/com.aspose.slides/ifilloverlay/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

表示一种填充覆盖效果。填充覆盖可用于为对象指定额外的填充并将两种填充混合在一起。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Fill format. |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. 可读写 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**返回值：**
int

### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. 可读写 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Fill format. 只读 [IFillFormat](../../com.aspose.slides/ifillformat).

**返回值：**
[IFillFormat](../../com.aspose.slides/ifillformat)