---
title: GrayScale
second_title: Aspose.Slides Java API 參考
description: 表示灰階效果。
type: docs
url: /zh-hant/com.aspose.slides/grayscale/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**全部已實作的介面：**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

表示 Gray Scale 效果。將所有效果顏色值轉換為與其亮度相對應的灰色陰影。效果 alpha（opacity）值不受影響。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Gray Scale 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等於目前的 [GrayScale](../../com.aspose.slides/grayscale)。 |
| [hashCode()](#hashCode--) | 作為特定型別的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

取得套用繼承後的有效 Gray Scale 效果資料。

**返回值：**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - A [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [GrayScale](../../com.aspose.slides/grayscale) 是否等於目前的 [GrayScale](../../com.aspose.slides/grayscale)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [GrayScale](../../com.aspose.slides/grayscale)。 |

**返回值：**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定型別的雜湊函式。

**返回值：**
int - 目前物件的雜湊碼。