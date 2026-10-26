---
title: BiLevel
second_title: Aspose.Slides for Java API 參考
description: 表示一種 Bi-Level（黑/白）效果。
type: docs
url: /zh-hant/com.aspose.slides/bilevel/
---
**繼承：**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面：**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

表示一種 Bi-Level（black/white）效果。亮度低於指定閾值的輸入顏色會被變為黑色。亮度大於或等於指定值的輸入顏色會被設為白色。此效果不會影響 alpha 效果值。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Bi-Level 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [BiLevel](../../com.aspose.slides/bilevel) 是否等於目前的 [BiLevel](../../com.aspose.slides/bilevel)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

取得套用繼承後的有效 Bi-Level 效果資料。

**傳回值：**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - A [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [BiLevel](../../com.aspose.slides/bilevel) 是否等於目前的 [BiLevel](../../com.aspose.slides/bilevel)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [BiLevel](../../com.aspose.slides/bilevel)。 |

**傳回值：**
boolean - 如果物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回值：**
int - 目前物件的雜湊碼。