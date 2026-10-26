---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
插入指定版面投影片的副本到集合中的指定位置。

### 回傳

插入的投影片。

```python
def insert_clone(self, index, source_layout):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要克隆的投影片。 |

### 備註

新的版面配置將與此版面投影片集合的母版投影片連結。這相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。

### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`MasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterlayoutslidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)