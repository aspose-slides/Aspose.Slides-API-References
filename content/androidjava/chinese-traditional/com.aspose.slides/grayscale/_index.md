---
title: GrayScale
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示灰階效果。
type: docs
url: /zh-hant/com.aspose.slides/grayscale/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**  
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect  
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

表示灰階效果。將所有效果顏色值轉換為相對於其亮度的灰色陰影。效果的 alpha（不透明度）值不受影響。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 獲取套用繼承後的有效灰階效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等於當前的 [GrayScale](../../com.aspose.slides/grayscale)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

獲取套用繼承後的有效灰階效果資料。

**傳回值:**  
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - 一個 [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等於當前的 [GrayScale](../../com.aspose.slides/grayscale)。

**參數:**  

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [GrayScale](../../com.aspose.slides/grayscale)。 |

**傳回值:**  
boolean - 若物件相等則返回 true；否則返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回值:**  
int - 當前物件的雜湊碼。