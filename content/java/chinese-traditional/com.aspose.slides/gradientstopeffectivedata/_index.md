---
title: GradientStopEffectiveData
second_title: Aspose.Slides for Java API 參考文件
description: 不可變的物件，代表一個漸層停止點。
type: docs
url: /zh-hant/com.aspose.slides/gradientstopeffectivedata/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
com.aspose.slides.IEffectiveData, [com.aspose.slides.IGradientStopEffectiveData](../../com.aspose.slides/igradientstopeffectivedata)  
```
public class GradientStopEffectiveData implements IEffectiveData, IGradientStopEffectiveData
```

不可變的物件，代表一個漸層停止點。  
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPosition()](#getPosition--) | 傳回漸層停止點的位置 (0..1)。 |
| [getColor()](#getColor--) | 傳回漸層停止點的顏色。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata) 是否等於目前的 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)。 |
| [hashCode()](#hashCode--) |  |
### getPosition() {#getPosition--}
```
public final float getPosition()
```

傳回漸層停止點的位置 (0..1)。唯讀 float.

**傳回:**  
float
### getColor() {#getColor--}
```
public final Color getColor()
```

傳回漸層停止點的顏色。唯讀 java.awt.Color.

**傳回:**  
java.awt.Color
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata) 是否等於目前的 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [GradientStopEffectiveData](../../com.aspose.slides/gradientstopeffectivedata)。 |

**傳回:**  
boolean - true if objects are equal; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

**傳回:**  
int