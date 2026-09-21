---
title: FontFallBackRule class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/fontfallbackrule/
---
## FontFallBackRule 類別

表示字體回退規則

FontFallBackRule 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/__init__/#int-int-str) | 建立新實例。 |
| [`__init__(self, start_index, end_index, font_names)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/__init__/#int-int-liststr) | 建立新實例。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`range_start_index`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/range_start_index/) | 取得連續 Unicode 範圍的第一個索引。 |
| [`range_end_index`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/range_end_index/) | 取得連續 Unicode 範圍的最後一個索引。 |
| [`count`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/count/) | 取得實際在範圍內定義的字體數量。<br/>            唯讀 **int**。 |

取得指定索引處的字體名稱。            唯讀 [`IFontFallBackRule`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule)。

## 索引子

| 名稱 | 說明 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/__getitem__/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/add_fall_back_fonts/#str) | 將新字體（們）加入回退字體清單。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/add_fall_back_fonts/#liststr) | 將新字體加入回退字體清單。 |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/to_array/#) | 建立並傳回包含此規則所有回退字體的陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/to_array/#int-int) | 建立並傳回列表中指定範圍內所有回退字體的陣列。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/clear/#) | 從清單中移除所有字體。 |
| [`remove(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/remove/#str) | 從清單中移除特定回退字體的第一次出現。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/remove_at/#int) | 從清單中移除指定索引處的回退字體。 |
| [`index_of(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/fontfallbackrule/index_of/#str) | 傳回集合中指定規則的索引。 |


### 另請參閱
* 類別 [`IFontFallBackRule`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)