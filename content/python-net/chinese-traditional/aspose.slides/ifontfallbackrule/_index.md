---
title: IFontFallBackRule class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ifontfallbackrule/
---
## IFontFallBackRule 類別

代表字型回退規則

IFontFallBackRule 類型公開以下成員：

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`range_start_index`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/range_start_index/) | 取得連續 Unicode 範圍的第一個索引。 |
| [`range_end_index`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/range_end_index/) | 取得連續 Unicode 範圍的最後一個索引。 |
| [`count`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/count/) | 取得此範圍實際定義的字型數量。 |

取得指定索引處的字型名稱。

## 索引子

| 名稱 | 描述 |
| :- | :- |
| [`[index]`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/__getitem__/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`add_fall_back_fonts(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#str) | 將新的字型（或多個字型）新增至回退字型清單。 |
| [`add_fall_back_fonts(self, font_names)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/add_fall_back_fonts/#liststr) | 將新的字型新增至回退字型清單。 |
| [`to_array(self)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/to_array/#) | 建立並回傳此規則的所有回退字型陣列。 |
| [`to_array(self, start_index, count)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/to_array/#int-int) | 建立並回傳清單中指定範圍的所有回退字型陣列。 |
| [`clear(self)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/clear/#) | 從清單中移除所有字型。 |
| [`remove(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/remove/#str) | 從清單中移除第一個出現的特定回退字型。 |
| [`remove_at(self, index)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/remove_at/#int) | 從清單中移除指定索引的回退字型。 |
| [`index_of(self, font_name)`](/slides/python-net/zh-hant/aspose.slides/ifontfallbackrule/index_of/#str) | 回傳集合中指定規則的索引。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)