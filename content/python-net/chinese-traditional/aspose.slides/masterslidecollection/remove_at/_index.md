---
title: remove_at method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
移除集合中指定索引的元素。

```python
def remove_at(self, index):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要移除的元素的零基索引。 |

### 備註

為避免拋出 PptxEditException，請先檢查 master 的 HasDependingSlides 屬性。

### 例外

| 例外 | 說明 |
| :- | :- |
| [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception) | 若要移除的 master 正在簡報中被使用（其 HasDependingSlides 屬性為 true），則拋出此例外。 |

### 另見
* 類別 [`MasterSlideCollection`](/slides/python-net/zh-hant/aspose.slides/masterslidecollection)
* 類別 [`PptxEditException`](/slides/python-net/zh-hant/aspose.slides/pptxeditexception)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)