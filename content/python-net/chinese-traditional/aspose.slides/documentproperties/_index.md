---
title: DocumentProperties class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/documentproperties/
---
## DocumentProperties 類別

代表簡報的屬性。

DocumentProperties 類型公開以下成員：

## 建構函式

| 建構函式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/__init__/#) | 初始化 [`DocumentProperties`](/slides/python-net/zh-hant/aspose.slides/documentproperties) 類別的新執行個體。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`app_version`](/slides/python-net/zh-hant/aspose.slides/documentproperties/app_version/) | 返回應用程式版本。<br/>            只讀 **str**。 |
| [`name_of_application`](/slides/python-net/zh-hant/aspose.slides/documentproperties/name_of_application/) | 返回或設定應用程式的名稱。<br/>            可讀寫 **str**。 |
| [`company`](/slides/python-net/zh-hant/aspose.slides/documentproperties/company/) | 返回或設定公司屬性。<br/>            可讀寫 **str**。 |
| [`manager`](/slides/python-net/zh-hant/aspose.slides/documentproperties/manager/) | 返回或設定管理者屬性。<br/>            可讀寫 **str**。 |
| [`presentation_format`](/slides/python-net/zh-hant/aspose.slides/documentproperties/presentation_format/) | 返回或設定簡報的目標格式。<br/>            可讀寫 **str**。 |
| [`shared_doc`](/slides/python-net/zh-hant/aspose.slides/documentproperties/shared_doc/) | 判斷簡報是否在多個使用者之間共享。<br/>            可讀寫 **bool**。 |
| [`application_template`](/slides/python-net/zh-hant/aspose.slides/documentproperties/application_template/) | 返回或設定應用程式的範本。<br/>            可讀寫 **str**。 |
| [`total_editing_time`](/slides/python-net/zh-hant/aspose.slides/documentproperties/total_editing_time/) | 簡報的總編輯時間。<br/>            可讀寫 **System.TimeSpan**。 |
| [`title`](/slides/python-net/zh-hant/aspose.slides/documentproperties/title/) | 返回或設定簡報的標題。<br/>            可讀寫 **str**。 |
| [`subject`](/slides/python-net/zh-hant/aspose.slides/documentproperties/subject/) | 返回或設定簡報的主旨。<br/>            可讀寫 **str**。 |
| [`author`](/slides/python-net/zh-hant/aspose.slides/documentproperties/author/) | 返回或設定簡報的作者。<br/>            可讀寫 **str**。 |
| [`keywords`](/slides/python-net/zh-hant/aspose.slides/documentproperties/keywords/) | 返回或設定簡報的關鍵字。<br/>            可讀寫 **str**。 |
| [`comments`](/slides/python-net/zh-hant/aspose.slides/documentproperties/comments/) | 返回或設定簡報的備註。<br/>            可讀寫 **str**。 |
| [`category`](/slides/python-net/zh-hant/aspose.slides/documentproperties/category/) | 返回或設定簡報的類別。<br/>            可讀寫 **str**。 |
| [`created_time`](/slides/python-net/zh-hant/aspose.slides/documentproperties/created_time/) | 返回簡報的建立日期。<br/>            值為 UTC 時間。<br/>            可讀寫 **System.DateTime**。 |
| [`last_saved_time`](/slides/python-net/zh-hant/aspose.slides/documentproperties/last_saved_time/) | 返回簡報最後一次修改的日期。<br/>            值為 UTC 時間。<br/>            在 Presentation.DocumentProperties 情況下為只讀（因為在 IPresentation 物件保存過程中會內部更新）。<br/>            可透過由方法 [`IPresentationInfo.read_document_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/read_document_properties) 回傳的 DocumentProperties 實例進行變更。<br/>            請參考 **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** 方法說明中的範例。 |
| [`last_printed`](/slides/python-net/zh-hant/aspose.slides/documentproperties/last_printed/) | 返回簡報最近一次列印的日期。<br/>            可讀寫 **System.DateTime**。 |
| [`last_saved_by`](/slides/python-net/zh-hant/aspose.slides/documentproperties/last_saved_by/) | 返回或設定最後一次修改簡報的使用者名稱。<br/>            可讀寫 **str**。 |
| [`revision_number`](/slides/python-net/zh-hant/aspose.slides/documentproperties/revision_number/) | 返回或設定簡報的版本號。<br/>            可讀寫 **int**。 |
| [`content_status`](/slides/python-net/zh-hant/aspose.slides/documentproperties/content_status/) | 返回或設定簡報的內容狀態。<br/>            可讀寫 **str**。 |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/documentproperties/content_type/) | 返回或設定簡報的內容類型。<br/>            可讀寫 **str**。 |
| [`hyperlink_base`](/slides/python-net/zh-hant/aspose.slides/documentproperties/hyperlink_base/) | 返回或設定 HyperlinkBase 文件屬性。<br/>            可讀寫 **str**。 |
| [`count_of_custom_properties`](/slides/python-net/zh-hant/aspose.slides/documentproperties/count_of_custom_properties/) | 返回集合中實際包含的自訂屬性數量。<br/>            只讀 **int**。 |
| [`scale_crop`](/slides/python-net/zh-hant/aspose.slides/documentproperties/scale_crop/) | 指示文件縮圖的顯示模式。<br/>            設定此元素為 **true** 可將文件縮圖縮放至符合顯示。<br/>            設定此元素為 **false** 可裁切文件縮圖，只顯示適合顯示的部分。<br/>            可讀寫 **bool**。 |
| [`links_up_to_date`](/slides/python-net/zh-hant/aspose.slides/documentproperties/links_up_to_date/) | 指示文件中的超連結是否為最新。<br/>            設定此元素為 **true** 表示超連結已更新。<br/>            設定此元素為 **false** 表示超連結已過時。<br/>            可讀寫 **bool**。 |
| [`hyperlinks_changed`](/slides/python-net/zh-hant/aspose.slides/documentproperties/hyperlinks_changed/) | 指定此部份中的一個或多個超連結僅由產生者在此部份更新。<br/>            下一個開啟此文件的產生者應使用此部份指定的新超連結更新超連結關係。<br/>            可讀寫 **bool**。 |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/documentproperties/slides/) | 返回簡報文件中的投影片總數。<br/zh-hant/>            只讀 **int**。 |
| [`hidden_slides`](/slides/python-net/zh-hant/aspose.slides/documentproperties/hidden_slides/) | 返回簡報文件中隱藏的投影片數量。<br/>            只讀 **int**。 |
| [`notes`](/slides/python-net/zh-hant/aspose.slides/documentproperties/notes/) | 返回包含註解的投影片數量。<br/>            只讀 **int**。 |
| [`paragraphs`](/slides/python-net/zh-hant/aspose.slides/documentproperties/paragraphs/) | 返回文件中找到的段落總數（若適用）。<br/>            只讀 **int**。 |
| [`words`](/slides/python-net/zh-hant/aspose.slides/documentproperties/words/) | 返回文件中包含的單詞總數。<br/>            只讀 **int**。 |
| [`multimedia_clips`](/slides/python-net/zh-hant/aspose.slides/documentproperties/multimedia_clips/) | 返回文件中存在的音訊或影片剪輯總數。<br/>            只讀 **int**。 |
| [`titles_of_parts`](/slides/python-net/zh-hant/aspose.slides/documentproperties/titles_of_parts/) | 指定每個文件部份的標題。<br/>            這些部份不是實際文件部份，而是文件章節的概念表示。<br/>            只讀 **List[str]**。 |
| [`heading_pairs`](/slides/python-net/zh-hant/aspose.slides/documentproperties/heading_pairs/) | 指示文件部份的分組以及每個組中的部份數量。<br/>            只讀 **List[IHeadingPair]**。 |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) | 從自訂屬性取得具名布林值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) | 從自訂屬性取得具名整數值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) | 從自訂屬性取得具名 DateTime 值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) | 從自訂屬性取得具名字串值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-bool) | 設定具名布林自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-int) | 設定具名整數自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-datetime) | 設定具名 DateTime 自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-str) | 設定具名字串自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-float) | 設定具名浮點數自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/set_custom_property_value/#str-float) | 設定具名雙精度自訂屬性。 |
| [`get_custom_property_name(self, index)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_custom_property_name/#int) | 在指定索引處返回自訂屬性名稱。 |
| [`remove_custom_property(self, name)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/remove_custom_property/#str) | 移除與指定名稱關聯的自訂屬性。 |
| [`contains_custom_property(self, name)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/contains_custom_property/#str) | 檢查是否存在具有指定名稱的自訂屬性。 |
| [`clear_custom_properties(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/clear_custom_properties/#) | 移除所有自訂屬性。 |
| [`get_sensitivity_labels(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/get_sensitivity_labels/#) | 從自訂文件屬性取得敏感性標籤陣列（Microsoft Information Protection SDK 中的 Metadata）。 |
| [`clear_built_in_properties(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/clear_built_in_properties/#) | 清除並設定所有內建屬性的預設值。 |
| [`clone(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/clone/#) | 複製目前物件 |
| [`clone_t(self)`](/slides/python-net/zh-hant/aspose.slides/documentproperties/clone_t/#) | 複製目前物件 |


### 另請參閱
* 類別 [`DocumentProperties`](/slides/python-net/zh-hant/aspose.slides/documentproperties)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)