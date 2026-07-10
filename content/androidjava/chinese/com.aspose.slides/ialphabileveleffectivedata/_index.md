---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Android 的 Java API 参考
description: 表示 Alpha 双层效果的不可变对象。
type: docs
url: /zh/com.aspose.slides/ialphabileveleffectivedata/
---
**所有实现的接口：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

表示 Alpha 双层效果的不可变对象。Alpha（不透明度）值小于阈值的将被更改为 0（完全透明），大于或等于阈值的将被更改为 100%（完全不透明）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回效果阈值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


返回效果阈值。只读浮点数。

**返回：**
float