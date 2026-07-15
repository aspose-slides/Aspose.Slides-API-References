---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: 定義一個平面，用於相對於其所應用的形狀施加如發光與陰影等效果。
type: docs
url: /zh-hant/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

定義一個平面，用於相對於其所應用的形狀施加如發光與陰影等效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | 返回或設定法向量。 |
| [setNormalVector(float[] value)](#setNormalVector-float---) | 返回或設定法向量。 |
| [getAnchorPoint()](#getAnchorPoint--) | 返回或設定三維空間中的點。 |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | 返回或設定三維空間中的點。 |
| [getUpVector()](#getUpVector--) | 返回或設定表示向上方向的向量。 |
| [setUpVector(float[] value)](#setUpVector-float---) | 返回或設定表示向上方向的向量。 |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


返回或設定法向量。更精確地說，此屬性定義一個垂直於背景平面面的向量。向量以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回值:**  
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


返回或設定法向量。更精確地說，此屬性定義一個垂直於背景平面面的向量。向量以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


返回或設定三維空間中的點。此點是用於錨定背景平面的空間點。三維點以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回值:**  
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


返回或設定三維空間中的點。此點是用於錨定背景平面的空間點。三維點以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


返回或設定表示向上方向的向量。更精確地說，此屬性定義一個相對於背景平面面的向上向量。向量以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**返回值:**  
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


返回或設定表示向上方向的向量。更精確地說，此屬性定義一個相對於背景平面面的向上向量。向量以包含 X、Y 與 Z 座標的 3 個 float 值的陣列表示。讀/寫 float[]。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | float[] |  