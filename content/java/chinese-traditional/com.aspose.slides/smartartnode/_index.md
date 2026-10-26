---
title: SmartArtNode
second_title: Aspose.Slides for Java API 參考
description: 表示 SmartArt 物件的節點
type: docs
url: /zh-hant/com.aspose.slides/smartartnode/
---
**繼承：**
java.lang.Object

**已實作的所有介面：**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

表示 SmartArt 物件的節點
## 方法

| 方法 | 描述 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 返回目前節點的所有子節點集合。 |
| [getShapes()](#getShapes--) | 返回與節點關聯的所有圖形集合。 |
| [getTextFrame()](#getTextFrame--) | 返回節點的文字框。 |
| [isAssistant()](#isAssistant--) | 取得或設定節點為助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 取得或設定節點為助理。 |
| [getLevel()](#getLevel--) | 返回節點的巢狀層級。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 返回包含節點項目符號填充格式屬性的 FillFormat 物件。 |
| [getPosition()](#getPosition--) | 取得或設定節點在同級節點中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 取得或設定節點在同級節點中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此節點在資料模型中為隱藏節點，則返回 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 取得或設定與目前節點相關聯的組織圖版面配置類型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 取得或設定與目前節點相關聯的組織圖版面配置類型。 |
| [remove()](#remove--) | 移除目前節點。 |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

返回目前節點的所有子節點集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

返回與節點關聯的所有圖形集合。唯讀 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**返回：**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

返回節點的文字框。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

取得或設定節點為助理。可讀寫 boolean。

**返回：**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

取得或設定節點為助理。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```

返回節點的巢狀層級。唯讀 int。

**返回：**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

返回包含節點項目符號填充格式屬性的 FillFormat 物件。注意：對於某些不提供節點項目符號的 SmartArt 版面配置，可能返回 null。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

取得或設定節點在同級節點中的零基位置。可讀寫 int。

**返回：**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

取得或設定節點在同級節點中的零基位置。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

返回 true，如果此節點在資料模型中為隱藏節點。唯讀 boolean。

**返回：**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

取得或設定與目前節點相關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**返回：**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

取得或設定與目前節點相關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```

移除目前節點。

**返回：**
boolean - true if removed succesfully, otherwise false