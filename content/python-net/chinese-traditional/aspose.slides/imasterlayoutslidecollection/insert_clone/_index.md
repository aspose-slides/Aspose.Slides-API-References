---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
將指定版面投影片的副本插入至集合的指定位置。

### 回傳值

已插入的投影片。

```python
def insert_clone(self, index, source_layout):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要複製的投影片。 |

### 備註

新版面將會與此版面投影片集合的父母主投影片連結。  
因此此操作相當於在 PowerPoint 中使用「使用目標佈景主題」選項的複製/貼上。

### 另見
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterlayoutslidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)