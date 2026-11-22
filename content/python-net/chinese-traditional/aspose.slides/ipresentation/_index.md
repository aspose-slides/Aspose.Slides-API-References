---
title: IPresentation class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentation/
---
## IPresentation 類別

簡報文件

IPresentation 類型公開以下成員：

## 屬性

| 屬性 | 描述 |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh-hant/aspose.slides/ipresentation/current_date_time/) | 傳回或設定日期和時間，此時間將取代 datetime 欄位的內容。<br/>            此 Presentation 物件建立時的時間，預設值。<br/>            讀寫 **System.DateTime**。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/header_footer_manager/) | 傳回簡報的 HeaderFooter 管理器。<br/>            唯讀 [`IPresentationHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/ipresentationheaderfootermanager)。 |
| [`protection_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/protection_manager/) | 取得此簡報的權限管理器。<br/>            唯讀 [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager)。 |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/slides/) | 傳回簡報中定義的所有投影片清單。<br/zh-hant/>            唯讀 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection)。 |
| [`sections`](/slides/python-net/zh-hant/aspose.slides/ipresentation/sections/) | 傳回簡報中定義的所有投影片分段清單。<br/>            唯讀 [`ISectionCollection`](/slides/python-net/zh-hant/aspose.slides/isectioncollection)。 |
| [`slide_size`](/slides/python-net/zh-hant/aspose.slides/ipresentation/slide_size/) | 傳回投影片大小物件。<br/>            唯讀 [`ISlideSize`](/slides/python-net/zh-hant/aspose.slides/islidesize)。 |
| [`notes_size`](/slides/python-net/zh-hant/aspose.slides/ipresentation/notes_size/) | 傳回備註投影片大小物件。<br/>            唯讀 [`INotesSize`](/slides/python-net/zh-hant/aspose.slides/inotessize)。 |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/ipresentation/layout_slides/) | 傳回簡報中定義的所有版面配置投影片清單。<br/>            唯讀 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection)。 |
| [`masters`](/slides/python-net/zh-hant/aspose.slides/ipresentation/masters/) | 傳回簡報中定義的所有主投影片清單。<br/>            唯讀 [`IMasterSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterslidecollection)。 |
| [`master_notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_notes_slide_manager/) | 傳回備註主管理器。<br/>            唯讀 [`IMasterNotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasternotesslidemanager)。 |
| [`master_handout_slide_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_handout_slide_manager/) | 傳回講義主管理器。<br/>            唯讀 [`IMasterHandoutSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslidemanager)。 |
| [`fonts_manager`](/slides/python-net/zh-hant/aspose.slides/ipresentation/fonts_manager/) | 傳回字型管理器。<br/>            唯讀 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager)。 |
| [`default_text_style`](/slides/python-net/zh-hant/aspose.slides/ipresentation/default_text_style/) | 傳回形狀的預設文字樣式。<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`comment_authors`](/slides/python-net/zh-hant/aspose.slides/ipresentation/comment_authors/) | 傳回評論作者的集合。<br/>            唯讀 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection)。 |
| [`document_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentation/document_properties/) | 傳回 DocumentProperties 物件，該物件包含標準與自訂的文件屬性。<br/>            唯讀 [`IDocumentProperties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties)。 |
| [`images`](/slides/python-net/zh-hant/aspose.slides/ipresentation/images/) | 傳回簡報中所有影像的集合。<br/>            唯讀 [`IImageCollection`](/slides/python-net/zh-hant/aspose.slides/iimagecollection)。 |
| [`audios`](/slides/python-net/zh-hant/aspose.slides/ipresentation/audios/) | 傳回簡報中所有內嵌音訊檔案的集合。<br/>            唯讀 [`IAudioCollection`](/slides/python-net/zh-hant/aspose.slides/iaudiocollection)。 |
| [`videos`](/slides/python-net/zh-hant/aspose.slides/ipresentation/videos/) | 傳回簡報中所有內嵌視訊檔案的集合。<br/>            唯讀 [`IVideoCollection`](/slides/python-net/zh-hant/aspose.slides/ivideocollection)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/ipresentation/custom_data/) | 傳回簡報的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`vba_project`](/slides/python-net/zh-hant/aspose.slides/ipresentation/vba_project/) | 取得含有簡報巨集的 VBA 專案。<br/>            讀寫 [`IVbaProject`](/slides/python-net/zh-hant/aspose.slides.vba/ivbaproject)。 |
| [`source_format`](/slides/python-net/zh-hant/aspose.slides/ipresentation/source_format/) | 傳回簡報載入自哪種格式的資訊。<br/>            唯讀 [`IPresentation.source_format`](/slides/python-net/zh-hant/aspose.slides/ipresentation/source_format)。 |
| [`master_theme`](/slides/python-net/zh-hant/aspose.slides/ipresentation/master_theme/) | 傳回簡報的主題樣式。<br/>            唯讀 [`IMasterTheme`](/slides/python-net/zh-hant/aspose.slides.theme/imastertheme)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/ipresentation/hyperlink_queries/) | 提供對所有簡報投影片（不含主投影片、版面配置、備註投影片）中超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`view_properties`](/slides/python-net/zh-hant/aspose.slides/ipresentation/view_properties/) | 取得簡報全域檢視屬性。<br/>            唯讀 [`IViewProperties`](/slides/python-net/zh-hant/aspose.slides/iviewproperties)。 |
| [`first_slide_number`](/slides/python-net/zh-hant/aspose.slides/ipresentation/first_slide_number/) | 表示簡報中的第一張投影片編號。<br/>            讀寫 **int**。 |
| [`all_custom_xml_parts`](/slides/python-net/zh-hant/aspose.slides/ipresentation/all_custom_xml_parts/) | 傳回簡報中所有自訂資料部件。<br/>            唯讀 [`ICustomXmlPart`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpart)[]。 |
| [`digital_signatures`](/slides/python-net/zh-hant/aspose.slides/ipresentation/digital_signatures/) | 傳回用於簽署簡報的簽章集合。<br/>            唯讀 [`IDigitalSignatureCollection`](/slides/python-net/zh-hant/aspose.slides/idigitalsignaturecollection)。 |
| [`sensitivity_labels`](/slides/python-net/zh-hant/aspose.slides/ipresentation/sensitivity_labels/) | 傳回套用於簡報文件的敏感度標籤集合。<br/>            唯讀 [`ISensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabelcollection)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/ipresentation/presentation/) |  |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat) | 將簡報的所有投影片儲存為指定格式的檔案。 |
| [`save(self, stream, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat) | 將簡報的所有投影片以指定格式儲存至串流。 |
| [`save(self, fname, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報的所有投影片儲存為指定格式的檔案，並套用額外選項。 |
| [`save(self, stream, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報的所有投影片以指定格式儲存至串流，並套用額外選項。 |
| [`save(self, fname, slides, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat) | 將簡報中指定的投影片儲存為指定格式的檔案。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報中指定的投影片儲存為指定格式的檔案。 |
| [`save(self, stream, slides, format)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 將簡報中指定的投影片以指定格式儲存至串流。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報中指定的投影片以指定格式儲存至串流。 |
| [`save(self, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/save/#asposeslidesexportxamlixamloptions) | 將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。 |
| [`get_images(self, options)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions) | 傳回簡報所有投影片的縮圖影像物件。 |
| [`get_images(self, options, slides)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint) | 傳回簡報中指定投影片的縮圖位圖物件。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 傳回簡報所有投影片的縮圖影像物件（自訂縮放）。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 傳回簡報中指定投影片的縮圖影像物件（自訂縮放）。 |
| [`get_images(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 傳回簡報所有投影片的縮圖影像物件（指定尺寸）。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 傳回簡報中指定投影片的縮圖影像物件（指定尺寸）。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/get_slide_by_id/#int) | 依 Id 傳回 Slide、MasterSlide 或 LayoutSlide。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/join_portions_with_same_formatting/#) | 在所有投影片的所有可接受形狀的段落中，合併格式相同的文字串。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/highlight_regex/#str-asposeslidescolor) | 以指定顏色突顯正規表達式的所有匹配項目。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 將所有指定文字的出現處替換為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/replace_regex/#str-str) | 將正規表達式的所有匹配項目替換為指定字串。 |
| [`refresh_charts_data(self, skip_failed_charts)`](/slides/python-net/zh-hant/aspose.slides/ipresentation/refresh_charts_data/#bool) | 重新從來源活頁簿載入簡報中所有圖表的資料。 |

### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)