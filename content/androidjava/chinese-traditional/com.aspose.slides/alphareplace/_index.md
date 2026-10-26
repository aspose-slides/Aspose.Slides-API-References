---
title: AlphaReplace
second_title: Aspose.Slides for Android via Java API 參考
description: 代表 Alpha Replace 效果。
type: docs
url: /zh-hant/com.aspose.slides/alphareplace/
---
**繼承:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**已實作的介面:**
[com.aspose.slides.IAlphaReplace](../../com.aspose.slides/ialphareplace), com.aspose.slides.IVisualEffect
```
public final class AlphaReplace extends ImageTransformOperation implements IAlphaReplace, IVisualEffect
```

代表 Alpha Replace 效果。效果的 alpha（不透明度）值將被固定的 alpha 取代。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效 Alpha Replace 效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [AlphaReplace](../../com.aspose.slides/alphareplace) 是否等於目前的 [AlphaReplace](../../com.aspose.slides/alphareplace)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式使用。 |
### getEffective() {#getEffective--}
```
public final IAlphaReplaceEffectiveData getEffective()
```

取得套用繼承後的有效 Alpha Replace 效果資料。

**回傳值:**
[IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata) - 一個 [IAlphaReplaceEffectiveData](../../com.aspose.slides/ialphareplaceeffectivedata)。

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [AlphaReplace](../../com.aspose.slides/alphareplace) 是否等於目前的 [AlphaReplace](../../com.aspose.slides/alphareplace)。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [AlphaReplace](../../com.aspose.slides/alphareplace)。 |

**回傳值:**
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式使用。

**回傳值:**
int - 目前物件的雜湊碼。