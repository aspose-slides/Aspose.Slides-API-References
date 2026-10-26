---
title: MasterNotesSlideHeaderFooterManager class
second_title: Aspose.Slides 適用於 Python 透過 .NET 的 API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/masternotesslideheaderfootermanager/
---
## MasterNotesSlideHeaderFooterManager 類別

代表管理器，負責掌管主註解投影片的頁腳、日期時間、頁碼佔位符以及所有子佔位符的行為。  
子佔位符表示佔位符位於相依的註解投影片上。  
相依的註解投影片使用且依賴於主註解投影片。

**繼承:**[`MasterNotesSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager) → [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/basehandoutnotesslideheaderfootermanager) → [`BaseSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/baseslideheaderfootermanager) → [`BaseHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/baseheaderfootermanager)

MasterNotesSlideHeaderFooterManager 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`is_footer_visible`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/is_footer_visible/) | 取得指示是否存在頁腳佔位符的值。<br/>            讀取 **bool**. |
| [`is_slide_number_visible`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/is_slide_number_visible/) | 取得指示是否存在頁碼佔位符的值。<br/>            讀取**bool**. |
| [`is_date_time_visible`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/is_date_time_visible/) | 取得指示是否存在日期時間佔位符的值。<br/>            讀取**bool**. |
| [`is_header_visible`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/is_header_visible/) | 取得指示是否存在標題佔位符的值。<br/>            讀取 **bool**. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`set_footer_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_footer_visibility/#bool) | 變更投影片頁腳佔位符的可見性。 |
| [`set_slide_number_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_visibility/#bool) | 變更投影片頁碼佔位符的可見性。 |
| [`set_date_time_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_date_time_visibility/#bool) | 變更投影片日期時間佔位符的可見性。 |
| [`set_footer_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_footer_text/#str) | 設定投影片頁腳佔位符的文字。 |
| [`set_date_time_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_date_time_text/#str) | 設定投影片日期時間佔位符的文字。 |
| [`set_header_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_header_visibility/#bool) | 變更投影片標題佔位符的可見性。 |
| [`set_header_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_header_text/#str) | 設定投影片標題佔位符的文字。 |
| [`set_header_and_child_headers_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_visibility/#bool) | 變更主註解投影片標題佔位符以及所有子標題佔位符的可見性。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_header_and_child_headers_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_header_and_child_headers_text/#str) | 設定主註解投影片標題佔位符以及所有子標題佔位符的文字。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_footer_and_child_footers_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_visibility/#bool) | 變更主投影片頁腳佔位符以及所有子頁腳佔位符的可見性。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_slide_number_and_child_slide_numbers_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_slide_number_and_child_slide_numbers_visibility/#bool) | 變更主投影片頁碼佔位符以及所有子頁碼佔位符的可見性。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_date_time_and_child_date_times_visibility(self, is_visible)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_visibility/#bool) | 變更主投影片日期時間佔位符以及所有子日期時間佔位符的可見性。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_footer_and_child_footers_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_footer_and_child_footers_text/#str) | 設定主投影片頁腳佔位符以及所有子頁腳佔位符的文字。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |
| [`set_date_time_and_child_date_times_text(self, text)`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager/set_date_time_and_child_date_times_text/#str) | 設定主投影片日期時間佔位符以及所有子日期時間佔位符的文字。<br/>            子佔位符表示佔位符位於相依的註解投影片上。<br/>            相依的註解投影片使用且依賴於主註解投影片。 |

### 另請參閱
* 類別 [`BaseHandoutNotesSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/basehandoutnotesslideheaderfootermanager)
* 類別 [`BaseHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/baseheaderfootermanager)
* 類別 [`BaseSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/baseslideheaderfootermanager)
* 類別 [`MasterNotesSlideHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/masternotesslideheaderfootermanager)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)