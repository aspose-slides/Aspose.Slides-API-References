---
title: IPictureFrame
second_title: Aspose.Slides for Android via Java API 参考
description: 表示一个包含图片的框架。
type: docs
url: /zh/com.aspose.slides/ipictureframe/
---
**所有已实现的接口:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IPictureFrame extends IGeometryShape
```

表示一个包含图片的框架。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPictureFrameLock()](#getPictureFrameLock--) | 返回 PictureFrame 的锁定。 |
| [getPictureFormat()](#getPictureFormat--) | 返回图片框架的 PictureFillFormat 对象。 |
| [getRelativeScaleHeight()](#getRelativeScaleHeight--) | 返回或设置图片框架的高度比例（相对于原始图片尺寸）。 |
| [setRelativeScaleHeight(float value)](#setRelativeScaleHeight-float-) | 返回或设置图片框架的高度比例（相对于原始图片尺寸）。 |
| [getRelativeScaleWidth()](#getRelativeScaleWidth--) | 返回或设置图片框架的宽度比例（相对于原始图片尺寸）。 |
| [setRelativeScaleWidth(float value)](#setRelativeScaleWidth-float-) | 返回或设置图片框架的宽度比例（相对于原始图片尺寸）。 |
### getPictureFrameLock() {#getPictureFrameLock--}
```
public abstract IPictureFrameLock getPictureFrameLock()
```

返回 PictureFrame 的锁定。只读 [IPictureFrameLock](../../com.aspose.slides/ipictureframelock)。

**返回:**
[IPictureFrameLock](../../com.aspose.slides/ipictureframelock)
### getPictureFormat() {#getPictureFormat--}
```
public abstract IPictureFillFormat getPictureFormat()
```

返回图片框架的 PictureFillFormat 对象。只读 [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)。

**返回:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRelativeScaleHeight() {#getRelativeScaleHeight--}
```
public abstract float getRelativeScaleHeight()
```

返回或设置图片框架的高度比例（相对于原始图片尺寸）。值 1.0 对应 100%。读写 float。

**返回:**
float
### setRelativeScaleHeight(float value) {#setRelativeScaleHeight-float-}
```
public abstract void setRelativeScaleHeight(float value)
```

返回或设置图片框架的高度比例（相对于原始图片尺寸）。值 1.0 对应 100%。读写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |
### getRelativeScaleWidth() {#getRelativeScaleWidth--}
```
public abstract float getRelativeScaleWidth()
```

返回或设置图片框架的宽度比例（相对于原始图片尺寸）。值 1.0 对应 100%。读写 float。

**返回:**
float
### setRelativeScaleWidth(float value) {#setRelativeScaleWidth-float-}
```
public abstract void setRelativeScaleWidth(float value)
```

返回或设置图片框架的宽度比例（相对于原始图片尺寸）。值 1.0 对应 100%。读写 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |