---
title: ISmartArt
second_title: Aspose.Slides for Java API 參考
description: 表示 SmartArt 圖表。
type: docs
url: /zh-hant/com.aspose.slides/ismartart/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

代表一個 SmartArt 圖表。
## 方法

| Method | 說明 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 傳回 SmartArt 物件中所有節點的集合。 |
| [getNodes()](#getNodes--) | 傳回 SmartArt 物件中根節點的集合。 |
| [getLayout()](#getLayout--) | 取得或設定 SmartArt 物件的版面配置。 |
| [setLayout(int value)](#setLayout-int-) | 取得或設定 SmartArt 物件的版面配置。 |
| [getQuickStyle()](#getQuickStyle--) | 取得或設定 SmartArt 物件的快速樣式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 取得或設定 SmartArt 物件的快速樣式。 |
| [getColorStyle()](#getColorStyle--) | 取得或設定 SmartArt 物件的色彩樣式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 取得或設定 SmartArt 物件的色彩樣式。 |
| [isReversed()](#isReversed--) | 取得或設定 SmartArt 圖表的狀態，以決定左至右 (LTR) 或右至左 (RTL)，若圖表支援翻轉。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 取得或設定 SmartArt 圖表的狀態，以決定左至右 (LTR) 或右至左 (RTL)，若圖表支援翻轉。 |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

傳回 SmartArt 物件中所有節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**傳回值：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

傳回 SmartArt 物件中根節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**傳回值：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

取得或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**傳回值：**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

取得或設定 SmartArt 物件的版面配置。讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

取得或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**傳回值：**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickShape(int value)
```

取得或設定 SmartArt 物件的快速樣式。讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

取得或設定 SmartArt 物件的色彩樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**傳回值：**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

取得或設定 SmartArt 物件的色彩樣式。讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

取得或設定 SmartArt 圖表的狀態，以決定左至右 (LTR) 或右至左 (RTL)，若圖表支援翻轉。讀寫 boolean。

**傳回值：**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

取得或設定 SmartArt 圖表的狀態，以決定左至右 (LTR) 或右至左 (RTL)，若圖表支援翻轉。讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |