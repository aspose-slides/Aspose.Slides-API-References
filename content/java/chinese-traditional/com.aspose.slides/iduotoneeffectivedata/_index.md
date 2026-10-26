---
title: IDuotoneEffectiveData
second_title: Aspose.Slides Java API 參考
description: 不可變的物件，代表雙色調效果。
type: docs
url: /zh-hant/com.aspose.slides/iduotoneeffectivedata/
---
**已實作的所有介面：**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

不可變的物件，代表雙色調效果。對於每個像素，通過線性插值將 clr1 與 clr2 結合，以確定該像素的新顏色。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getColor1()](#getColor1--) | 返回暗像素的目標顏色格式。 |
| [getColor2()](#getColor2--) | 返回亮像素的目標顏色格式。 |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


返回暗像素的目標顏色格式。只讀 java.awt.Color.

**傳回值：**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


返回亮像素的目標顏色格式。只讀 java.awt.Color。

**傳回值：**
java.awt.Color