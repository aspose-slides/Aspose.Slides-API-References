---
title: AlphaFloor
second_title: Aspose.Slides for Android via Java API 參考
description: 表示 Alpha Floor 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphafloor/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作介面：**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

表示 Alpha Floor 效果。Alpha（opacity）值小於 100% 的會被設為零。換句話說，任何部分透明的物件都會變為完全透明。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Floor 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaFloor](../../com.aspose.slides/alphafloor) 是否等於目前的 [AlphaFloor](../../com.aspose.slides/alphafloor)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Floor 效果資料。

**返回：**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - 一個 [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata)。
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaFloor](../../com.aspose.slides/alphafloor) 是否等於目前的 [AlphaFloor](../../com.aspose.slides/alphafloor)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaFloor](../../com.aspose.slides/alphafloor)。 |

**返回：**
boolean - 若物件相等則為 true；否則為 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**返回：**
int - 目前物件的雜湊碼。