---
title: IColorReplaceEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變物件，表示顏色替換效果。
type: docs
url: /zh-hant/com.aspose.slides/icolorreplaceeffectivedata/
---
**所有已實作的介面:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorReplaceEffectiveData extends IEffectEffectiveData
```

不可變物件，表示顏色替換效果。所有效果顏色皆會變更為固定顏色。Alpha 值不受影響。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColor()](#getColor--) | 傳回將取代每個像素顏色的色彩格式。 |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


傳回將取代每個像素顏色的色彩格式。唯讀 java.awt.Color.

**傳回:** 
java.awt.Color