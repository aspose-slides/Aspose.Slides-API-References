---
title: Blur
second_title: Aspose.Slides for Java API 參考
description: 表示套用於整個形狀（包括其填充）的模糊效果。
type: docs
url: /zh-hant/com.aspose.slides/blur/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**已實作的介面:**  
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect  
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

表示套用於整個圖形（包括其填充）的模糊效果。所有色彩通道（包括 alpha）均會受到影響。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getRadius()](#getRadius--) | 傳回或設定模糊半徑。 |
| [setRadius(double value)](#setRadius-double-) | 傳回或設定模糊半徑。 |
| [getGrow()](#getGrow--) | 決定是否應因模糊而擴大物件的邊界。 |
| [setGrow(boolean value)](#setGrow-boolean-) | 決定是否應因模糊而擴大物件的邊界。 |
| [getEffective()](#getEffective--) | 取得套用了繼承的有效模糊效果資料。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 判斷指定的 [Blur](../../com.aspose.slides/blur) 是否等於目前的 [Blur](../../com.aspose.slides/blur)。 |
| [hashCode()](#hashCode--) | 作為特定類型的雜湊函式。 |

### getRadius() {#getRadius--}
```
public final double getRadius()
```

傳回或設定模糊半徑。讀寫 double。

**傳回：**  
double

### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

傳回或設定模糊半徑。讀寫 double。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```

決定是否因模糊而擴大物件的邊界。True 表示邊界會被擴大，false 表示不會。讀寫 boolean。

**傳回：**  
boolean

### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```

決定是否因模糊而擴大物件的邊界。True 表示邊界會被擴大，false 表示不會。讀寫 boolean。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```

取得套用了繼承的有效模糊效果資料。

**傳回：**  
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - A [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

判斷指定的 [Blur](../../com.aspose.slides/blur) 是否等於目前的 [Blur](../../com.aspose.slides/blur)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | java.lang.Object | 用於比較的 [Blur](../../com.aspose.slides/blur)。 |

**傳回：**  
boolean - 若物件相等則為 true；否則為 false。

### hashCode() {#hashCode--}
```
public int hashCode()
```

作為特定類型的雜湊函式。

**傳回：**  
int - 目前物件的雜湊碼。