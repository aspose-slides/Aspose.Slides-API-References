---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
將指定投影片的副本新增至集合的末端。

### 回傳值

New slide.



```python
def add_clone(self, source_slide):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |

### 備註

在不同簡報之間克隆投影片時，投影片的母片也可能被克隆。  
使用內部註冊表追蹤自動克隆的母片，以防止同一母片產生多個克隆。  
手動克隆母片既不會被阻止，也不會被註冊。  
如果需要對克隆過程有更多控制，請使用  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** 或  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 來克隆投影片，  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** 或  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 來克隆版面配置，以及  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 來克隆母片。


## add_clone(self, source_slide, section) {#islide-isection}
將指定投影片的副本新增至指定區段的末端。

### 回傳值

New slide.



```python
def add_clone(self, source_slide, section):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 新投影片的區段。 |

### 例外狀況

| 例外狀況 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
將指定投影片的副本新增至集合的末端。

### 回傳值

New slide.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 新投影片的版面配置投影片。 |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
將指定來源投影片的副本新增至集合的末端。  
系統會自動從指定的 master 中選取合適的版面配置（合適的版面配置是與來源投影片的版面配置具有相同 Type 或 Name 的版面配置）。如果沒有合適的版面配置，則會克隆來源投影片的版面配置 (如果 allowCloneMissingLayout 為 true) <br/><br/> 或拋出 PptxEditException (如果 allowCloneMissingLayout 為 false)。

### 回傳值

New slide.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新投影片的母片。 |
| allow_clone_missing_layout | **bool** | 如果在指定的 master 中沒有適當的版面配置，則會克隆來源投影片的版面配置 (如果 allowCloneMissingLayout 為 true) <br/><br/> 或拋出 PptxEditException (如果 allowCloneMissingLayout 為 false)。 |

### 例外狀況

| 例外狀況 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 當在指定的 master 中沒有適當的版面配置且 allowCloneMissingLayout 為 false 時拋出。 |



### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)