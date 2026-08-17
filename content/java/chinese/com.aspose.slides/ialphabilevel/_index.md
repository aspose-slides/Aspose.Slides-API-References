---
title: IAlphaBiLevel
second_title: Aspose.Slides Java API 参考
description: 表示 Alpha 双层效果。
type: docs
url: /zh/com.aspose.slides/ialphabilevel/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

表示 Alpha 双层效果。Alpha (Opacity) 值小于阈值的将被更改为 0（完全透明），Alpha 值大于或等于阈值的将被更改为 100%（完全不透明）。

--------------------

使用 ImageTransformOperationFactory 在 COM 中创建实例。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returns effect threshold. |
| [setThreshold(float value)](#setThreshold-float-) | Returns effect threshold. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

返回效果阈值。读取/写入 float。

**返回:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

返回效果阈值。读取/写入 float。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |