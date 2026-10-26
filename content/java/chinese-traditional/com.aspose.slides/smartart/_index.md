---
title: SmartArt
second_title: Aspose.Slides for Java API 參考
description: 表示一個 SmartArt 圖表
type: docs
url: /zh-hant/com.aspose.slides/smartart/
---
**繼承:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**已實作的介面:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

代表一個 SmartArt 圖表
## 方法

| 方法 | 說明 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 傳回 SmartArt 物件中所有節點的集合。 |
| [getNodes()](#getNodes--) | 傳回 SmartArt 物件中根節點的集合。 |
| [getLayout()](#getLayout--) | 傳回或設定 SmartArt 物件的版面配置。 |
| [setLayout(int value)](#setLayout-int-) | 傳回或設定 SmartArt 物件的版面配置。 |
| [getQuickStyle()](#getQuickStyle--) | 傳回或設定 SmartArt 物件的快速樣式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 傳回或設定 SmartArt 物件的快速樣式。 |
| [getColorStyle()](#getColorStyle--) | 傳回或設定 SmartArt 物件的顏色樣式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 傳回或設定 SmartArt 物件的顏色樣式。 |
| [isReversed()](#isReversed--) | 傳回或設定 SmartArt 圖表相對於 (由左至右) LTR 或 (由右至左) RTL 的狀態，若圖表支援反轉。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 傳回或設定 SmartArt 圖表相對於 (由左至右) LTR 或 (由右至左) RTL 的狀態，若圖表支援反轉。 |

### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

傳回 SmartArt 物件中所有節點的集合。只讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

傳回 SmartArt 物件中根節點的集合。只讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public final int getLayout()
```

傳回或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**返回：**
int

### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

傳回或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

傳回或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**返回：**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

傳回或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

傳回或設定 SmartArt 物件的顏色樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**返回：**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

傳回或設定 SmartArt 物件的顏色樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

傳回或設定 SmartArt 圖表相對於 (由左至右) LTR 或 (由右至左) RTL 的狀態，若圖表支援反轉。讀寫  boolean 。

**返回：**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

傳回或設定 SmartArt 圖表相對於 (由左至右) LTR 或 (由右至左) RTL 的狀態，若圖表支援反轉。讀寫  boolean 。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |