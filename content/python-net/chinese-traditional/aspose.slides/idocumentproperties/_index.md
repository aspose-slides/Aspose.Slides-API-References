---
title: IDocumentProperties class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/idocumentproperties/
---
## IDocumentProperties 類別

表示簡報的屬性。

IDocumentProperties 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`app_version`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/app_version/) | 傳回應用程式版本。<br/>            唯讀 **str**. |
| [`name_of_application`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/name_of_application/) | 取得或設定應用程式的名稱。<br/>            讀寫 **str**. |
| [`company`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/company/) | 取得或設定公司屬性。<br/>            讀寫 **str**. |
| [`manager`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/manager/) | 取得或設定主管屬性。<br/>            讀寫 **str**. |
| [`presentation_format`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/presentation_format/) | 取得或設定簡報的目標格式。<br/>            讀寫 **str**. |
| [`shared_doc`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/shared_doc/) | 判斷簡報是否在多個使用者之間共享。<br/>            讀寫 **bool**. |
| [`application_template`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/application_template/) | 取得或設定應用程式的範本。<br/>            讀寫 **str**. |
| [`total_editing_time`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/total_editing_time/) | 簡報的總編輯時間。<br/>            讀寫 **System.TimeSpan**. |
| [`title`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/title/) | 取得或設定簡報的標題。<br/>            讀寫 **str**. |
| [`subject`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/subject/) | 取得或設定簡報的主旨。<br/>            讀寫 **str**. |
| [`author`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/author/) | 取得或設定簡報的作者。<br/>            讀寫 **str**. |
| [`keywords`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/keywords/) | 取得或設定簡報的關鍵字。<br/>            讀寫 **str**. |
| [`comments`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/comments/) | 取得或設定簡報的註解。<br/>            讀寫 **str**. |
| [`category`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/category/) | 取得或設定簡報的類別。<br/>            讀寫 **str**. |
| [`created_time`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/created_time/) | 傳回簡報建立的日期。<br/>            值為 UTC。<br/>            讀寫 **System.DateTime**. |
| [`last_saved_time`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/last_saved_time/) | 傳回簡報最後修改的日期。<br/>            值為 UTC。<br/>            在 Presentation.DocumentProperties 情況下為唯讀（因為在 IPresentation 物件儲存過程中會內部更新）。<br/>            可透過方法 [`IPresentationInfo.read_document_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentationinfo/read_document_properties) 回傳的 DocumentProperties 實例變更。<br/>            請參閱 **Aspose.Slides.IPresentationInfo.UpdateDocumentProperties(Aspose.Slide** 方法說明中的範例。 |
| [`last_printed`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/last_printed/) | 傳回簡報上一次列印的日期。<br/>            讀寫 **System.DateTime**. |
| [`last_saved_by`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/last_saved_by/) | 取得或設定最後修改簡報之人的名稱。<br/>            讀寫 **str**. |
| [`revision_number`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/revision_number/) | 取得或設定簡報的修訂編號。<br/>            讀寫 **int**. |
| [`content_status`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/content_status/) | 取得或設定簡報的內容狀態。<br/>            讀寫 **str**. |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/content_type/) | 取得或設定簡報的內容類型。<br/>            讀寫 **str**. |
| [`hyperlink_base`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/hyperlink_base/) | 取得或設定 HyperlinkBase 文件屬性。<br/>            讀寫 **str**. |
| [`scale_crop`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/scale_crop/) | 指示文件縮圖的顯示模式。<br/>            將此元素設為 **true** 以允許將文件縮圖縮放至顯示區域。<br/>            將此元素設為 **false** 以裁剪文件縮圖，只顯示適合顯示區域的部分。<br/>            讀寫 **bool**. |
| [`links_up_to_date`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/links_up_to_date/) | 指示文件中的超連結是否為最新。<br/>            將此元素設為 **true** 以表示超連結已更新。<br/>            將此元素設為 **false** 以表示超連結已過時。<br/>            讀寫 **bool**. |
| [`hyperlinks_changed`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/hyperlinks_changed/) | 指定此部份中的一或多個超連結僅由產製者在此部份更新。<br/>            下一個開啟此文件的產製者應使用此部份中指定的新超連結更新超連結關係。<br/>            讀寫 **bool**. |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/slides/) | 指定簡報文件中投影片的總數。<br/zh-hant/>            唯讀 **int**. |
| [`hidden_slides`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/hidden_slides/) | 指定簡報文件中隱藏投影片的數量。<br/>            唯讀 **int**. |
| [`notes`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/notes/) | 指定含有備註的投影片數量。<br/>            唯讀 **int**. |
| [`paragraphs`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/paragraphs/) | 指定文件中找到的段落總數（如適用）。<br/>            唯讀 **int**. |
| [`words`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/words/) | 指定文件中包含的單詞總數。<br/>            唯讀 **int**. |
| [`multimedia_clips`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/multimedia_clips/) | 指定文件中出現的音訊或視訊剪輯的總數。<br/>            唯讀 **int**. |
| [`titles_of_parts`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/titles_of_parts/) | 指定每個文件部份的標題。<br/>            這些部份不是文件部份，而是文件區段的概念性表示。<br/>            唯讀 **List[str]**. |
| [`heading_pairs`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/heading_pairs/) | 指示文件部份的分組以及每個群組中的部份數量。<br/>            唯讀 **List[IHeadingPair]**. |
| [`count_of_custom_properties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/count_of_custom_properties/) | 傳回集合中實際包含的自訂屬性數量。<br/>            唯讀 **int**. |

## 方法

| Method | Description |
| :- | :- |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 從自訂屬性中取得具名布林值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 從自訂屬性中取得具名整數值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 從自訂屬性中取得具名 DateTime 值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) | 從自訂屬性中取得具名字串值。 |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`get_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_value/#str-any) |  |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-bool) | 設定具名布林自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-int) | 設定具名整數自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-datetime) | 設定具名 DateTime 自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-str) | 設定具名字串自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 設定具名浮點數自訂屬性。 |
| [`set_custom_property_value(self, name, value)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/set_custom_property_value/#str-float) | 設定具名雙精度浮點數自訂屬性。 |
| [`get_custom_property_name(self, index)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_custom_property_name/#int) | 於指定索引返回自訂屬性名稱。 |
| [`remove_custom_property(self, name)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/remove_custom_property/#str) | 移除與指定名稱相關聯的自訂屬性。 |
| [`contains_custom_property(self, name)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/contains_custom_property/#str) | 檢查是否存在具名自訂屬性。 |
| [`clear_custom_properties(self)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/clear_custom_properties/#) | 移除所有自訂屬性。 |
| [`clear_built_in_properties(self)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/clear_built_in_properties/#) | 清除並為所有內建屬性設定預設值。 |
| [`get_sensitivity_labels(self)`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties/get_sensitivity_labels/#) | 從自訂文件屬性取得敏感度標籤陣列（Microsoft Information Protection SDK Metadata）。 |

### 參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)