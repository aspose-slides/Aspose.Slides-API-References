---
title: GlobalLayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/globallayoutslidecollection/
---
## GlobalLayoutSlideCollection 類別

表示簡報中所有版面投影片的集合。  
擴充 LayoutSlideCollection 類別，提供在合併各個母版版面投影片集合的情境下，新增/複製 版面投影片的方法。

**Inheritance:**[`GlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection) → [`LayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection)

GlobalLayoutSlideCollection 類型公開以下成員：

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_clone(self, source_layout)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide) | 將指定的版面投影片的副本新增至簡報。 |
| [`add_clone(self, source_layout, dest_master)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/add_clone/#ilayoutslide-imasterslide) | 將指定的版面投影片的副本新增至簡報。 |
| [`get_by_type(self, type)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/get_by_type/#slidelayouttype) | 傳回指定類型的第一個版面投影片。<br/>            要尋找的版面投影片類型。[`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide) 具有指定類型，若未找到版面則回傳 None。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/remove/#ilayoutslide) | 從集合中移除版面。 |
| [`remove_unused(self)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/remove_unused/#) | 移除未使用的版面投影片（HasDependingSlides 為 false 的版面投影片）。 |
| [`add(self, master, layout_type, layout_name)`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection/add/#imasterslide-slidelayouttype-str) | 將新的版面投影片新增至簡報。 |

### 另請參閱
* 類別 [`GlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection)
* 類別 [`LayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)