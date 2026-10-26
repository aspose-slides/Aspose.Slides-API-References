---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
將指定版面投影片的副本新增至簡報中。

### 返回值

已新增投影片。

```python
def add_clone(self, source_layout):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要克隆的投影片。 |

### 備註
When cloning a layout between different presentations layout's master can be cloned too
            以保留來源的格式。
            內部註冊表用於追蹤自動克隆的母片，以防止建立 
            相同母片的多個克隆。
            手動克隆母片既不會被阻止，也不會被註冊。

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
將指定版面投影片的副本新增至簡報中。

### 返回值

已新增投影片。

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要克隆的投影片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新版面的母片投影片。 |

### 備註
1) 新版面將會與目的簡報中定義的母片連結。
            因此這相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。
2) 此方法的類似方法是 **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            透過 [`IMasterSlide.layout_slides`](/slides/python-net/zh-hant/aspose.slides/imasterslide/layout_slides) 屬性存取。

### 另請參閱
* 類別 [`GlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/globallayoutslidecollection)
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)