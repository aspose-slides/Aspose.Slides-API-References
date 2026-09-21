---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
將指定投影片的複本新增至集合的末端。

### 傳回值

新的投影片。

```python
def add_clone(self, source_slide):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要複製的投影片。 |

### 備註

在不同簡報之間複製投影片時，投影片的母片也可能被複製。  
使用內部註冊表來追蹤自動複製的母片，以防止同一母片產生多個複本。  
不會阻止或註冊手動複製母片。  
如果需要對複製過程有更多控制，請使用  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** 或  
**Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** 來複製投影片，  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** 或  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** 來複製版面配置，以及  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** 來複製母片。

## add_clone(self, source_slide, section) {#islide-isection}
將指定投影片的複本新增至指定章節的末端。

### 傳回值

新的投影片。

```python
def add_clone(self, source_slide, section):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要複製的投影片。 |
| section | [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection) | 新投影片所屬的章節。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) |  |

## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
將指定投影片的複本新增至集合的末端。

### 傳回值

新的投影片。

```python
def add_clone(self, source_slide, dest_layout):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要複製的投影片。 |
| dest_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 新投影片的版面配置投影片。 |

## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
將指定來源投影片的複本新增至集合的末端。  
將自動從指定的母片中選取適當的版面配置（適當的版面配置是與來源投影片的版面配置具有相同類型或名稱的版面配置）。如果沒有適當的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。

### 傳回值

新的投影片。

```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide) | 要複製的投影片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新投影片的母片投影片。 |
| allow_clone_missing_layout | **bool** | 若指定的母片中沒有適當的版面配置，則會複製來源投影片的版面配置（若 allowCloneMissingLayout 為 true）或拋出 PptxEditException（若 allowCloneMissingLayout 為 false）。 |

### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 當指定的母片中沒有適當的版面配置且 allowCloneMissingLayout 為 false 時拋出此例外。 |

### 另見
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 類別 [`ISection`](/slides/python-net/zh-hant/aspose.slides/isection)
* 類別 [`ISlide`](/slides/python-net/zh-hant/aspose.slides/islide)
* 類別 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)