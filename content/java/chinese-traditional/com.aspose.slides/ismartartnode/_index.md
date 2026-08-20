---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /zh-hant/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

表示 SmartArt 圖表的節點。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | 回傳目前節點的所有子節點集合。 |
| [getShapes()](#getShapes--) | 回傳與節點關聯的所有圖形集合。 |
| [getTextFrame()](#getTextFrame--) | 回傳或設定節點的文字。 |
| [isAssistant()](#isAssistant--) | 回傳或設定該節點為助理。 |
| [setAssistant(boolean value)](#setAssistant-boolean-) | 回傳或設定該節點為助理。 |
| [getLevel()](#getLevel--) | 回傳節點的巢狀層級。 |
| [getBulletFillFormat()](#getBulletFillFormat--) | 回傳包含節點項目填充格式屬性的 FillFormat 物件。 |
| [getPosition()](#getPosition--) | 回傳或設定節點在兄弟節點中的零基位置。 |
| [setPosition(int value)](#setPosition-int-) | 回傳或設定節點在兄弟節點中的零基位置。 |
| [isHidden()](#isHidden--) | 如果此節點在資料模型中為隱藏節點，則回傳 true。 |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | 回傳或設定與目前節點關聯的組織圖版面配置類型。 |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | 回傳或設定與目前節點關聯的組織圖版面配置類型。 |
| [remove()](#remove--) | 移除目前節點。 |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


回傳目前節點的所有子節點集合。唯讀 [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)。

**回傳：**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


回傳與節點關聯的所有圖形集合。唯讀 [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)。

**回傳：**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


回傳或設定節點的文字。唯讀 [ITextFrame](../../com.aspose.slides/itextframe)。

**回傳：**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


回傳或設定該節點為助理。可讀寫 boolean。

**回傳：**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


回傳或設定該節點為助理。可讀寫 boolean。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


回傳節點的巢狀層級。唯讀 int。

**回傳：**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


回傳包含節點項目填充格式屬性的 FillFormat 物件。註：對於某些不提供節點項目的 SmartArt 版面配置，可能會回傳 null。唯讀 [IFillFormat](../../com.aspose.slides/ifillformat)。

**回傳：**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


回傳或設定節點在兄弟節點中的零基位置。可讀寫 int。

**回傳：**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


回傳或設定節點在兄弟節點中的零基位置。可讀寫 int。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


如果此節點在資料模型中為隱藏節點，則回傳 true。唯讀 boolean。

**回傳：**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


回傳或設定與目前節點關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**回傳：**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


回傳或設定與目前節點關聯的組織圖版面配置類型。可讀寫 [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


移除目前節點。

**回傳：**
boolean - 若成功移除則為 true，否則為 false。