---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
將指定的佈局投影片新增為演示文件的複本。

### 返回

已新增的投影片。



```python
def add_clone(self, source_layout):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要克隆的投影片。 |

### 備註

當在不同簡報之間克隆佈局時，佈局的母片也會被克隆，以保留來源格式。  
内部註冊表用於追蹤自動克隆的母片，以防止建立同一母片的多個克隆。  
手動克隆母片既不會被阻止，也不會被註冊。


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
將指定的佈局投影片新增為演示文件的複本。

### 返回

已新增的投影片.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide) | 要克隆的投影片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide) | 新佈局的母片投影片。 |

### 備註

新佈局將與目標簡報中定義的母片連結。因此它相當於在 PowerPoint 中使用「使用目標主題」選項的複製/貼上。



### 另見
* 類別 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection)
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`IMasterSlide`](/slides/python-net/zh-hant/aspose.slides/imasterslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)