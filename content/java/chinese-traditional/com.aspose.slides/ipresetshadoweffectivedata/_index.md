---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides for Java API 參考
description: 不可變的物件，代表預設陰影效果。
type: docs
url: /zh-hant/com.aspose.slides/ipresetshadoweffectivedata/
---
**所有已實作介面:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

不可變物件，表示預設陰影效果。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getDirection()](#getDirection--) | 陰影的方向。 |
| [getDistance()](#getDistance--) | 陰影的距離。 |
| [getShadowColor()](#getShadowColor--) | 陰影的顏色。 |
| [getPreset()](#getPreset--) | 預設。 |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

陰影的方向。唯讀 float.

**返回:**  
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

陰影的距離。唯讀 double.

**返回:**  
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

陰影的顏色。唯讀 java.awt.Color.

**返回:**  
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

預設。唯讀 [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**返回:**  
int