---
title: MasterLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterlayoutslidecollection/
---
## MasterLayoutSlideCollection 類別

代表已定義母投影片的所有版面投影片的集合。  
擴充 LayoutSlideCollection 類別，提供在母投影片的各個版面投影片集合中新增/插入/移除/克隆/重新排序版面投影片的方法。

**Inheritance:**[`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection)

MasterLayoutSlideCollection 類型會公開以下成員：

## Indexer

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/__getitem__/) |  |

## Methods

| Method | Description |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/get_by_type/#slidelayouttype) | 返回指定類型的第一個版面投影片。<br/>            要尋找的版面投影片類型。[`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide) 具有指定類型或若未找到版面則回傳 None。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/remove/#ilayoutslide) | 從集合中移除版面。 |
| [`remove_unused(self)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/remove_unused/#) | 移除未使用的版面投影片（HasDependingSlides 為 false 的版面投影片）。 |
| [`add_clone(self, source_layout)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/add_clone/#ilayoutslide) | 新增指定版面投影片的複本至集合末端。 |
| [`insert_clone(self, index, source_layout)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/insert_clone/#int-ilayoutslide) | 在集合的指定位置插入指定版面投影片的複本。 |
| [`add(self, layout_type, layout_name)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/add/#slidelayouttype-str) | 新增一個新的版面投影片至集合末端。 |
| [`insert(self, index, layout_type, layout_name)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/insert/#int-slidelayouttype-str) | 在集合的指定位置插入一個新的版面投影片。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/remove_at/#int) | 移除集合中指定索引處的元素。 |
| [`reorder(self, index, layout_slide)`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection/reorder/#int-ilayoutslide) | 將版面投影片從集合移動至指定位置。 |


### 另見
* 類別 [`LayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection)
* 類別 [`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)