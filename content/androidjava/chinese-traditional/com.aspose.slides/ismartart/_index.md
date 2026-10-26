---
title: ISmartArt
second_title: Aspose.Slides for Android Java API 參考
description: 表示一個 SmartArt 圖表。
type: docs
url: /zh-hant/com.aspose.slides/ismartart/
---
**所有已實作的介面：**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

表示一個 SmartArt 圖表。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | 傳回 SmartArt 物件中全部節點的集合。 |
| [getNodes()](#getNodes--) | 傳回 SmartArt 物件中根節點的集合。 |
| [getLayout()](#getLayout--) | 取得或設定 SmartArt 物件的版面配置。 |
| [setLayout(int value)](#setLayout-int-) | 取得或設定 SmartArt 物件的版面配置。 |
| [getQuickStyle()](#getQuickStyle--) | 取得或設定 SmartArt 物件的快速樣式。 |
| [setQuickStyle(int value)](#setQuickStyle-int-) | 取得或設定 SmartArt 物件的快速樣式。 |
| [getColorStyle()](#getColorStyle--) | 取得或設定 SmartArt 物件的顏色樣式。 |
| [setColorStyle(int value)](#setColorStyle-int-) | 取得或設定 SmartArt 物件的顏色樣式。 |
| [isReversed()](#isReversed--) | 取得或設定 SmartArt 圖表的方向狀態（左至右 LTR 或 右至左 RTL），如果圖表支援翻轉的話。 |
| [setReversed(boolean value)](#setReversed-boolean-) | 取得或設定 SmartArt 圖表的方向狀態（左至右 LTR 或 右至左 RTL），如果圖表支援翻轉的話。 |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```


傳回 SmartArt 物件中全部節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**傳回:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```


傳回 SmartArt 物件中根節點的集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**傳回:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```


取得或設定 SmartArt 物件的版面配置。可讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**傳回:**  
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```


取得或設定 SmartArt 物件的版面配置。可讀寫 [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```


取得或設定 SmartArt 物件的快速樣式。可讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**傳回:**  
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```


取得或設定 SmartArt 物件的快速樣式。可讀寫 [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```


取得或設定 SmartArt 物件的顏色樣式。可讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**傳回:**  
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```


取得或設定 SmartArt 物件的顏色樣式。可讀寫 [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```


取得或設定 SmartArt 圖表的方向狀態（左至右 LTR 或 右至左 RTL），如果圖表支援翻轉的話。可讀寫 boolean.

**傳回:**  
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```


取得或設定 SmartArt 圖表的方向狀態（左至右 LTR 或 右至左 RTL），如果圖表支援翻轉的話。可讀寫 boolean.

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |