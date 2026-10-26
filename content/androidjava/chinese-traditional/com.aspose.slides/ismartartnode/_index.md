---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: 表示 SmartArt 圖表的節點。
type: docs
url: /zh-hant/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

表示 SmartArt 圖表的節點。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 返回當前節點的所有子節點集合。 |
| [getShapes()](#getShapes--) | 返回與該節點關聯的所有圖形集合。 |
| [getTextFrame()](#getTextFrame--) | 返回或設定節點的文字。 |
| [isAssistant()](#isAssistant--) | 返回或設定節點為助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 返回或設定節點為助理。 |
| [getLevel()](#getLevel--) | 返回節點的巢狀層級。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 返回包含節點項目符號填充格式屬性的 FillFormat 物件。 |
| [getPosition()](#getPosition--) | 返回或設定節點在同層節點中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 返回或設定節點在同層節點中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此節點在資料模型中為隱藏節點，則返回 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 返回或設定與當前節點相關聯的組織圖版面配置類型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 返回或設定與當前節點相關聯的組織圖版面配置類型。 |
| [remove()](#remove--) | 移除當前節點。 |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


返回當前節點的所有子節點集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**返回：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


返回與該節點關聯的所有圖形集合。唯讀 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**返回：**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


返回或設定節點的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**返回：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


返回或設定節點為助理。可讀寫 boolean。

**返回：**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


返回或設定節點為助理。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


返回節點的巢狀層級。唯讀 int。

**返回：**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


返回包含節點項目符號填充格式屬性的 FillFormat 物件。注意：對於某些不提供節點項目符號的 SmartArt 版面配置，可能返回 null。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**返回：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


返回或設定節點在同層節點中的零基位置。可讀寫 int。

**返回：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


返回或設定節點在同層節點中的零基位置。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


如果此節點在資料模型中為隱藏節點，則返回 true。唯讀 boolean。

**返回：**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


返回或設定與當前節點相關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**返回：**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


返回或設定與當前節點相關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```


移除當前節點。

**返回：**
boolean - 若成功移除則為 true，否則為 false。