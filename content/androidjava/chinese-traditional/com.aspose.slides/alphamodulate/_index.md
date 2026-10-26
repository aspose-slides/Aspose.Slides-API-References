---
title: AlphaModulate
second_title: Aspose.Slides for Android 之 Java API 參考
description: 代表 Alpha Modulate 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphamodulate/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**全部已實作的介面:**  
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect  
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

代表 Alpha Modulate 效果。效果的 alpha（不透明度）值會乘以固定的百分比。效果容器指定一個包含要調整的 alpha 值的效果。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Modulate effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaModulate](../../com.aspose.slides/alphamodulate) is equal to the current [AlphaModulate](../../com.aspose.slides/alphamodulate). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Modulate 效果資料。

**回傳值:**  
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - 一個 [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaModulate](../../com.aspose.slides/alphamodulate) 是否等於目前的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。 |

**回傳值:**  
boolean - 若兩個物件相等則為 true；否則為 false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**回傳值:**  
int - 目前物件的雜湊碼。