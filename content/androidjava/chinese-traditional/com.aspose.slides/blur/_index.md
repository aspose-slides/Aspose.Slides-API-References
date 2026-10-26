---
title: Blur
second_title: Aspose.Slides for Android via Java API 參考
description: 表示套用於整個形狀（包括其填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/blur/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**所有已實作的介面:**  
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect  
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

表示一種套用於整個形狀（包括其填充）的模糊效果。所有顏色通道，包括 alpha，皆受影響。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getRadius()](#getRadius--) | 回傳或設定模糊半徑。 |
| [setRadius(double value)](#setRadius-double-) | 回傳或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 判斷物件的邊界是否因模糊而擴大。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 判斷物件的邊界是否因模糊而擴大。 |
| [getEffective()](#getEffective--) | 取得套用繼承後的有效模糊效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Blur](../../com.aspose.slides/blur) 是否等於目前的 [Blur](../../com.aspose.slides/blur)。 |
| [hashCode()](#hashCode--) | 用作特定類型的雜湊函式。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

回傳或設定模糊半徑。可讀寫 double。

**回傳:**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

回傳或設定模糊半徑。可讀寫 double。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

判斷物件的邊界是否因模糊而擴大。True 表示邊界會擴大，而 false 表示不會。可讀寫 boolean。

**回傳:**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

判斷物件的邊界是否因模糊而擴大。True 表示邊界會擴大，而 false 表示不會。可讀寫 boolean。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

取得套用繼承後的有效模糊效果資料。

**回傳:**  
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Blur](../../com.aspose.slides/blur) 是否等於目前的 [Blur](../../com.aspose.slides/blur)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比較的 [Blur](../../com.aspose.slides/blur)。 |

**回傳:**  
boolean - 若物件相等則返回 true；否則返回 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

用作特定類型的雜湊函式。

**回傳:**  
int - 目前物件的雜湊碼。