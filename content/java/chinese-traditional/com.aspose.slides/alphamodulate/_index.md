---
title: AlphaModulate
second_title: Aspose.Slides for Java API 參考
description: 表示 Alpha Modulate 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphamodulate/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作介面：**
[com.aspose.slides.IAlphaModulate](../../com.aspose.slides/ialphamodulate), com.aspose.slides.IVisualEffect
```
public final class AlphaModulate extends ImageTransformOperation implements IAlphaModulate, IVisualEffect
```

代表 Alpha Modulate 效果。效果 alpha（不透明度）值會乘以固定的百分比。效果容器指定一個包含要調變之 alpha 值的效果。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得在套用繼承後的有效 Alpha Modulate 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaModulate](../../com.aspose.slides/alphamodulate) 是否等於目前的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IAlphaModulateEffectiveData getEffective()
```

取得在套用繼承後的有效 Alpha Modulate 效果資料。

**回傳值：**
[IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata) - 一個 [IAlphaModulateEffectiveData](../../com.aspose.slides/ialphamodulateeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaModulate](../../com.aspose.slides/alphamodulate) 是否等於目前的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [AlphaModulate](../../com.aspose.slides/alphamodulate)。 |

**回傳值：**
boolean - 若物件相等則 true；否則 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**回傳值：**
int - 目前物件的雜湊碼。