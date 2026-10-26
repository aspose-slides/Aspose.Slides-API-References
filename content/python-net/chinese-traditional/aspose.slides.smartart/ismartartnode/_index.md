---
title: ISmartArtNode class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/ismartartnode/
---
## ISmartArtNode 類別

表示 SmartArt 圖表的節點。

ISmartArtNode 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`child_nodes`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/child_nodes/) | 回傳目前節點的所有子節點集合。<br/>            唯讀 [`ISmartArtNodeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnodecollection). |
| [`shapes`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/shapes/) | 回傳與該節點關聯的所有圖形集合。<br/>            唯讀 [`ISmartArtShapeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartshapecollection). |
| [`text_frame`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/text_frame/) | 回傳或設定節點的文字。<br/>            唯讀 [`ITextFrame`](/slides/python-net/zh-hant/aspose.slides/itextframe). |
| [`is_assistant`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/is_assistant/) | 回傳或設定節點為助理。<br/>            讀寫 **bool**. |
| [`level`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/level/) | 回傳節點的巢狀層級。<br/>            唯讀 **int**. |
| [`bullet_fill_format`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/bullet_fill_format/) | 回傳包含節點項目符號填充格式屬性的 FillFormat 物件。<br/>            注意：對於某些不提供節點項目符號的 SmartArt 版面配置，可能會回傳 None。<br/>            唯讀 [`IFillFormat`](/slides/python-net/zh-hant/aspose.slides/ifillformat). |
| [`position`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/position/) | 回傳或設定節點在同級節點中的零基索引位置。<br/>            讀寫 **int**. |
| [`is_hidden`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/is_hidden/) | 若此節點在資料模型中為隱藏節點，則回傳 true。<br/>            唯讀 **bool**. |
| [`organization_chart_layout`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/organization_chart_layout/) | 回傳或設定與目前節點關聯的組織圖版面配置類型。<br/>            讀寫 [`OrganizationChartLayoutType`](/slides/python-net/zh-hant/aspose.slides.smartart/organizationchartlayouttype). |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode/remove/#) | 移除目前節點。 |

### 另請參閱
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 程式庫 [`Aspose.Slides`](/slides/python-net)