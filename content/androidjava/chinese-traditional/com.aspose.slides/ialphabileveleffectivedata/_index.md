---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Android 之 Java API 參考
description: 不可變物件，表示 Alpha 雙層效果。
type: docs
url: /zh-hant/com.aspose.slides/ialphabileveleffectivedata/
---
**所有已實作的介面：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

不可變物件，表示 Alpha 雙層效果。Alpha（Opacity）值低於閾值的會被改為 0（完全透明），而大於或等於閾值的會被改為 100%（完全不透明）。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 傳回效果閾值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


傳回效果閾值。唯讀 float.

**傳回:**
float