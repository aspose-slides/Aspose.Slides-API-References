---
title: IDuotoneEffectiveData
second_title: Aspose.Slides 針對 Android 的 Java API 參考
description: 不可變物件，代表雙調效果。
type: docs
url: /zh-hant/com.aspose.slides/iduotoneeffectivedata/
---
**所有已實作的介面:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

不可變物件，代表雙調效果。對於每個像素，透過線性插值將 clr1 和 clr2 結合，以決定該像素的新顏色。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目標顏色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目標顏色格式。 |
### getColor1() {#getColor1--}
```
public abstract Integer getColor1()
```

返回暗像素的目標顏色格式。唯讀 java.lang.Integer.

**返回：**
java.lang.Integer
### getColor2() {#getColor2--}
```
public abstract Integer getColor2()
```

返回亮像素的目標顏色格式。唯讀 java.lang.Integer。

**返回：**
java.lang.Integer