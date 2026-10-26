---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Android via Java API 參考
description: 不可變物件，表示雙階層（黑/白）效果。
type: docs
url: /zh-hant/com.aspose.slides/ibileveleffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

不可變物件，表示雙階層（black/white）效果。亮度低於指定閾值的輸入顏色會被更改為黑色。亮度大於或等於指定值的輸入顏色則會被設定為白色。此效果不會影響 alpha 效果值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 返回閾值。 |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

返回閾值。Read-only float.

**返回:**  
float