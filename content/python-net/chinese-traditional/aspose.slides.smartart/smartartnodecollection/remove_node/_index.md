---
title: remove_node method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.smartart/smartartnodecollection/remove_node/
weight: 30
---
## remove_node(self, index) {#int}
依索引移除節點或子節點


```python
def remove_node(self, index):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 節點的零基索引 |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 索引小於 0。 -或- 索引等於或大於同層節點的數量 |


## remove_node(self, node) {#ismartartnode}
移除節點或子節點


```python
def remove_node(self, node):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| node | [`ISmartArtNode`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode) | 要移除的節點 |



### 相關參考
* 類別 [`ISmartArtNode`](/slides/python-net/zh-hant/aspose.slides.smartart/ismartartnode)
* 類別 [`SmartArtNodeCollection`](/slides/python-net/zh-hant/aspose.slides.smartart/smartartnodecollection)
* 模組 [`aspose.slides.smartart`](/slides/python-net/zh-hant/aspose.slides.smartart)
* 函式庫 [`Aspose.Slides`](/slides/python-net)