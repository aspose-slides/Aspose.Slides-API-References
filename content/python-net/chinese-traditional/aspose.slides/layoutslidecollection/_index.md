---
title: LayoutSlideCollection class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/layoutslidecollection/
---
## LayoutSlideCollection 類別

表示佈局投影片集合的基底類別。

LayoutSlideCollection 類型公開以下成員：

依索引傳回佈局投影片。  
唯讀 [`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide)。

## Indexer

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_by_type(self, type)`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection/get_by_type/#slidelayouttype) | 傳回指定類型的第一個佈局投影片。<br/>要查找的佈局投影片類型。[`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide) 具有指定類型的佈局投影片，若未找到則回傳 None。 |
| [`remove(self, value)`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection/remove/#ilayoutslide) | 從集合中移除佈局。 |
| [`remove_unused(self)`](/slides/python-net/zh-hant/aspose.slides/layoutslidecollection/remove_unused/#) | 移除未使用的佈局投影片（HasDependingSlides 為 false 的佈局投影片）。 |

### 另見
* 類別 [`LayoutSlide`](/slides/python-net/zh-hant/aspose.slides/layoutslide)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)