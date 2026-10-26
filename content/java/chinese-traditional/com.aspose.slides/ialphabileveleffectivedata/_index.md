---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變物件，表示 Alpha 雙層效果。
type: docs
url: /zh-hant/com.aspose.slides/ialphabileveleffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

不可變物件，表示 Alpha 雙層效果。Alpha（Opacity）值小於閾值的會被變為 0（完全透明），大於或等於閾值的會被變為 100%（完全不透明）。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回效果閾值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

返回效果閾值。唯讀 float.

**返回:**  
float