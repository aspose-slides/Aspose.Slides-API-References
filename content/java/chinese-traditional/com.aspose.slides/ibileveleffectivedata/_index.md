---
title: IBiLevelEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，表示雙層（黑/白）效果。
type: docs
url: /zh-hant/com.aspose.slides/ibileveleffectivedata/
---
**所有已實作的介面:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

不可變的物件，表示雙層（黑/白）效果。亮度小於指定閾值的輸入色彩會被更改為黑色。亮度大於或等於指定值的輸入色彩會被設定為白色。此效果不會影響 alpha 效果值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getThreshold()](#getThreshold--) | 傳回閾值。 |

### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

傳回閾值。唯讀 float。

**傳回值:**  
float