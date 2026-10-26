---
title: SmartArt
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表一個 SmartArt 圖表
type: docs
url: /zh-hant/com.aspose.slides/smartart/
---
**繼承：**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**所有已實作介面：**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

代表一個 SmartArt 圖表
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 返回 SmartArt 物件中所有節點的集合。 |
| [getNodes()](#getNodes--) | 返回 SmartArt 物件中根節點的集合。 |
| [getLayout()](#getLayout--) | 返回或設定 SmartArt 物件的版面配置。 |
| [setLayout(int value)](#setLayout-int-) | 返回或設定 SmartArt 物件的版面配置。 |
| [getQuickStyle()](#getQuickStyle--) | 返回或設定 SmartArt 物件的快速樣式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 返回或設定 SmartArt 物件的快速樣式。 |
| [getColorStyle()](#getColorStyle--) | 返回或設定 SmartArt 物件的顏色樣式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 返回或設定 SmartArt 物件的顏色樣式。 |
| [isReversed()](#isReversed--) | 返回或設定 SmartArt 圖表的狀態，以符合從左到右 (LTR) 或從右到左 (RTL)，若圖表支援反轉。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 返回或設定 SmartArt 圖表的狀態，以符合從左到右 (LTR) 或從右到左 (RTL)，若圖表支援反轉。 |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

返回 SmartArt 物件中所有節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

返回 SmartArt 物件中根節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```

返回或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**返回：**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

返回或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

返回或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**返回：**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

返回或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

返回或設定 SmartArt 物件的顏色樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**返回：**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

返回或設定 SmartArt 物件的顏色樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

返回或設定 SmartArt 圖表的狀態，以符合從左到右 (LTR) 或從右到左 (RTL)，若圖表支援反轉。讀寫 boolean 。

**返回：**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

返回或設定 SmartArt 圖表的狀態，以符合從左到右 (LTR) 或從右到左 (RTL)，若圖表支援反轉。讀寫 boolean 。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |