---
title: remove method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
從簡報中移除版面配置。


```python
def remove(self):
    ...
```


### 備註

為避免拋出 PptxEditException，請先檢查 layout 的 HasDependingSlides 屬性。


### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 拋出此例外如果版面已從簡報中移除，或版面在簡報中被使用（其 <br/>            HasDependingSlides 屬性為 true）。 |



### 另請參閱
* 類別 [`ILayoutSlide`](/slides/python-net/zh-hant/aspose.slides/ilayoutslide)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)