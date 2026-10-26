---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
將指定版面投影片的副本新增至集合的末端。

### 返回值

已添加投影片。

```python
def add_clone(self, source_layout):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要複製的投影片。 |

### 備註

1) 新的版面將會與此版面投影片集合的父主投影片連結。  
   因此這相當於在 PowerPoint 中使用「使用目的地佈景主題」選項的複製/貼上。  
2) 此方法的類似功能是 **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide**，透過 [`IPresentation.layout_slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/layout_slides) 屬性存取。

### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterlayoutslidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)