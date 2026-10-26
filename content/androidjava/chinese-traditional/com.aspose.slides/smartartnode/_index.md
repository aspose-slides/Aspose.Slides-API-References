---
title: SmartArtNode
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 表示 SmartArt 物件的節點
type: docs
url: /zh-hant/com.aspose.slides/smartartnode/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

表示 SmartArt 物件的節點
## 方法

| 方法 | 說明 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 傳回目前節點所有子節點的集合。 |
| [getShapes()](#getShapes--) | 傳回與節點相關聯的所有圖形的集合。 |
| [getTextFrame()](#getTextFrame--) | 傳回節點的文字框。 |
| [isAssistant()](#isAssistant--) | 傳回或設定節點為助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 傳回或設定節點為助理。 |
| [getLevel()](#getLevel--) | 傳回節點的嵌套層級。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 傳回包含節點項目符號填滿格式屬性的 FillFormat 物件。 |
| [getPosition()](#getPosition--) | 傳回或設定節點在同層節點中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 傳回或設定節點在同層節點中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此節點在資料模型中為隱藏節點，則傳回 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 傳回或設定與目前節點相關聯的組織圖版面配置類型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 傳回或設定與目前節點相關聯的組織圖版面配置類型。 |
| [remove()](#remove--) | 移除目前節點。 |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


傳回目前節點所有子節點的集合。 唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**傳回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


傳回與節點相關聯的所有圖形的集合。 唯讀 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**傳回：**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


傳回節點的文字框。 唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**傳回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


傳回或設定節點為助理。 可讀寫 boolean。

**傳回：**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


傳回或設定節點為助理。 可讀寫 boolean。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```


傳回節點的嵌套層級。 唯讀 int。

**傳回：**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


傳回包含節點項目符號填滿格式屬性的 FillFormat 物件。註：對於某些不提供項目符號的 SmartArt 版面配置，可能會傳回 null。 唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**傳回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


傳回或設定節點在同層節點中的零基位置。 可讀寫 int 。

**傳回：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


傳回或設定節點在同層節點中的零基位置。 可讀寫 int 。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


如果此節點在資料模型中為隱藏節點，則傳回 true。 唯讀 boolean。

**傳回：**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


傳回或設定與目前節點相關聯的組織圖版面配置類型。 可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**傳回：**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


傳回或設定與目前節點相關聯的組織圖版面配置類型。 可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```


移除目前節點。

**傳回：**
boolean - true if removed succesfully, otherwise false