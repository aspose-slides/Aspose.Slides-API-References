---
title: IFillOverlay
second_title: Aspose.Slides Java API 参考
description: 表示填充叠加效果。
type: docs
url: /zh/com.aspose.slides/ifilloverlay/
---
**所有实现的接口：**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

表示填充叠加效果。填充叠加可用于为对象指定额外的填充，并将两种填充混合在一起。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | 填充格式. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. 读/写 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**返回：**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. 读/写 [FillBlendMode](../../com.aspose.slides/fillblendmode).

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


填充格式. 只读 [IFillFormat](../../com.aspose.slides/ifillformat).

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)