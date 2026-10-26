---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Android via Java API 参考
description: 不可变对象，表示二值黑白效果。
type: docs
url: /zh/com.aspose.slides/ibileveleffectivedata/
---
**所有实现的接口:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

不可变对象，表示 Bi-Level (black/white) 效果。亮度低于指定阈值的输入颜色将被更改为黑色。亮度大于或等于指定值的输入颜色将被设置为白色。alpha 效果值不受此效果影响。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回阈值。 |

### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

返回阈值。只读 float.

**返回:**
float