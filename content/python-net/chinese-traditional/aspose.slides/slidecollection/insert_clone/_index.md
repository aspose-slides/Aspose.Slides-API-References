---
title: insert_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
在集合的指定位置插入指定投影片的副本。

### 返回值

已插入的投影片。



```python
def insert_clone(self, index, source_slide):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |

### 說明

在不同簡報之間克隆投影片時，投影片的母版也可能被克隆。  
使用內部註冊表來追蹤自動克隆的母版，以防止同一母版投影片被多次克隆。  
不會阻止或註冊手動克隆母版投影片。  
如果需要對克隆過程有更多控制，請使用  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** 或  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 來克隆投影片，以及  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 來克隆母版。  


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
在集合的指定位置插入指定投影片的副本。

### 返回值

已插入的投影片。



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 新投影片的版面配置投影片。 |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
在集合的指定位置插入指定來源投影片的副本。  
會自動從指定的母版中選擇相應的版面配置（相應的版面配置是與來源投影片的版面配置具有相同類型或名稱的版面配置）。如果沒有相應的版面配置，則會克隆<br/><br/>來源投影片的版面配置（如果 allowCloneMissingLayout 為 true），或拋出<br/><br/>PptxEditException（如果 allowCloneMissingLayout 為 false）。

### 返回值

已插入的投影片。



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 新投影片的索引。 |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要克隆的投影片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新投影片的母版投影片。 |
| allow_clone_missing_layout | **bool** | 如果在指定的母版中沒有相應的版面配置，則會克隆<br/><br/>來源投影片的版面配置（如果 allowCloneMissingLayout 為 true），或拋出<br/><br/>PptxEditException（如果 allowCloneMissingLayout 為 false）。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 如果在指定的母版中沒有相應的版面配置，且<br/>allowCloneMissingLayout 為 false，則拋出此例外。 |



### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 類別 [`SlideCollection`](/slides/python-net/zh-hant/aspose.slides/slidecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)