---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/
---
## Presentation 類別

表示 Microsoft PowerPoint 簡報。

Presentation 類型公開以下成員：

## 建構函式

| 建構式 | 說明 |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#) | 此建構式從頭建立新的簡報。<br/>            建立的簡報包含一張空白投影片。 |
| [`__init__(self, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#loadoptions) | 此建構式從頭建立新的簡報。<br/>            建立的簡報包含一張空白投影片。 |
| [`__init__(self, stream)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#iorawiobase) | 此建構式是讀取現有 Presentation 的主要機制。 |
| [`__init__(self, stream, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | 此建構式是讀取現有 Presentation 的主要機制。 |
| [`__init__(self, file)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#str) | 此建構式取得來源檔案路徑，從中<br/>             讀取 Presentation 的內容。 |
| [`__init__(self, file, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#str-loadoptions) | 此建構式取得來源檔案路徑，從中<br/>            讀取 Presentation 的內容。 |

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh-hant/aspose.slides/presentation/current_date_time/) | 取得或設定日期時間，用於取代 datetime 欄位的內容。<br/>            預設為此 Presentation 物件建立的時間。<br/>            可讀寫 **System.DateTime**。 |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/header_footer_manager/) | 取得實際的 HeaderFooter 管理員。<br/>            唯讀 [`IPresentationHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/ipresentationheaderfootermanager)。 |
| [`protection_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/protection_manager/) | 取得此簡報的權限管理員。<br/>            唯讀 [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager)。 |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/presentation/slides/) | 取得簡報中定義的所有投影片清單。<br/zh-hant/>            唯讀 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection)。 |
| [`sections`](/slides/python-net/zh-hant/aspose.slides/presentation/sections/) | 取得簡報中定義的所有投影片區段清單。<br/>            唯讀 [`ISectionCollection`](/slides/python-net/zh-hant/aspose.slides/isectioncollection)。 |
| [`slide_size`](/slides/python-net/zh-hant/aspose.slides/presentation/slide_size/) | 取得投影片尺寸物件。<br/>            唯讀 [`ISlideSize`](/slides/python-net/zh-hant/aspose.slides/islidesize)。 |
| [`notes_size`](/slides/python-net/zh-hant/aspose.slides/presentation/notes_size/) | 取得備註投影片尺寸物件。<br/>            唯讀 [`INotesSize`](/slides/python-net/zh-hant/aspose.slides/inotessize)。 |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/presentation/layout_slides/) | 取得簡報中定義的所有版面配置投影片清單。<br/>            唯讀 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection)。 |
| [`masters`](/slides/python-net/zh-hant/aspose.slides/presentation/masters/) | 取得簡報中定義的所有母片清單。<br/>            唯讀 [`IMasterSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterslidecollection)。 |
| [`master_notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/master_notes_slide_manager/) | 取得備註母片管理員。<br/>            唯讀 [`IMasterNotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasternotesslidemanager)。 |
| [`master_handout_slide_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/master_handout_slide_manager/) | 取得講義母片管理員。<br/>            唯讀 [`IMasterHandoutSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslidemanager)。 |
| [`fonts_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/fonts_manager/) | 取得字型管理員。<br/>            唯讀 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager)。 |
| [`default_text_style`](/slides/python-net/zh-hant/aspose.slides/presentation/default_text_style/) | 取得圖形的預設文字樣式。<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle)。 |
| [`comment_authors`](/slides/python-net/zh-hant/aspose.slides/presentation/comment_authors/) | 取得評論作者的集合。<br/>            唯讀 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection)。 |
| [`document_properties`](/slides/python-net/zh-hant/aspose.slides/presentation/document_properties/) | 取得 DocumentProperties 物件，其中包含標準與自訂的文件屬性。<br/>            唯讀 [`IDocumentProperties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties)。 |
| [`images`](/slides/python-net/zh-hant/aspose.slides/presentation/images/) | 取得簡報中所有影像的集合。<br/>            唯讀 [`IImageCollection`](/slides/python-net/zh-hant/aspose.slides/iimagecollection)。 |
| [`audios`](/slides/python-net/zh-hant/aspose.slides/presentation/audios/) | 取得簡報中所有嵌入式音訊檔案的集合。<br/>            唯讀 [`IAudioCollection`](/slides/python-net/zh-hant/aspose.slides/iaudiocollection)。 |
| [`videos`](/slides/python-net/zh-hant/aspose.slides/presentation/videos/) | 取得簡報中所有嵌入式視訊檔案的集合。<br/>            唯讀 [`IVideoCollection`](/slides/python-net/zh-hant/aspose.slides/ivideocollection)。 |
| [`slide_show_settings`](/slides/python-net/zh-hant/aspose.slides/presentation/slide_show_settings/) | 取得簡報的投影片放映設定。 |
| [`digital_signatures`](/slides/python-net/zh-hant/aspose.slides/presentation/digital_signatures/) | 取得用於簽署簡報的簽章集合。<br/>            唯讀 [`IDigitalSignatureCollection`](/slides/python-net/zh-hant/aspose.slides/idigitalsignaturecollection)。 |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/presentation/custom_data/) | 取得簡報的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata)。 |
| [`all_custom_xml_parts`](/slides/python-net/zh-hant/aspose.slides/presentation/all_custom_xml_parts/) | 取得簡報中所有自訂資料部件。<br/>            唯讀 [`ICustomXmlPart`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpart)[]。 |
| [`vba_project`](/slides/python-net/zh-hant/aspose.slides/presentation/vba_project/) | 取得或設定包含簡報巨集的 VBA 專案。<br/>            可讀寫 [`IVbaProject`](/slides/python-net/zh-hant/aspose.slides.vba/ivbaproject)。 |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/presentation/hyperlink_queries/) | 提供對所有簡報投影片中（不含母片、版面配置、備註投影片）超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries)。 |
| [`view_properties`](/slides/python-net/zh-hant/aspose.slides/presentation/view_properties/) | 取得簡報範圍的檢視屬性。<br/>            唯讀 [`IViewProperties`](/slides/python-net/zh-hant/aspose.slides/iviewproperties)。 |
| [`first_slide_number`](/slides/python-net/zh-hant/aspose.slides/presentation/first_slide_number/) | 代表簡報中第一張投影片的編號 |
| [`sensitivity_labels`](/slides/python-net/zh-hant/aspose.slides/presentation/sensitivity_labels/) | 取得套用於簡報文件的敏感度標籤集合。<br/>            唯讀 [`ISensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabelcollection)。 |
| [`source_format`](/slides/python-net/zh-hant/aspose.slides/presentation/source_format/) | 取得簡報載入自哪種格式的資訊。<br/>            唯讀 [`SourceFormat`](/slides/python-net/zh-hant/aspose.slides/sourceformat)。 |
| [`master_theme`](/slides/python-net/zh-hant/aspose.slides/presentation/master_theme/) | 取得母片主題。<br/>            唯讀 [`IMasterTheme`](/slides/python-net/zh-hant/aspose.slides.theme/imastertheme)。 |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/presentation/presentation/) |  |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | 將簡報的所有投影片以指定格式儲存至檔案。 |
| [`save(self, stream, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | 將簡報的所有投影片以指定格式儲存至串流。 |
| [`save(self, fname, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報的所有投影片以指定格式儲存至串流，並使用額外選項。 |
| [`save(self, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | 將簡報的所有投影片儲存為一組代表 XAML 標記的檔案。 |
| [`save(self, fname, slides, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) | 將指定的投影片以指定格式儲存至檔案，並保留頁碼。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將指定的投影片以指定格式儲存至檔案，並保留頁碼。 |
| [`save(self, stream, slides, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) | 將指定的投影片以指定格式儲存至串流，並保留頁碼。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將指定的投影片以指定格式儲存至串流，並保留頁碼。 |
| [`get_images(self, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) | 取得簡報所有投影片的 Image 物件。 |
| [`get_images(self, options, slides)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) | 取得指定投影片的縮圖 Image 物件。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) | 取得簡報所有投影片的縮圖 Image 物件，使用自訂縮放。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) | 取得指定投影片的縮圖 Image 物件，使用自訂縮放。 |
| [`get_images(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposeslidessize) | 取得簡報所有投影片的縮圖 Image 物件，使用指定尺寸。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposeslidessize) | 取得指定投影片的縮圖 Image 物件，使用指定尺寸。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_text/#str-asposeslidescolor) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_text/#str-asposeslidescolor-itextsearchoptions-ifindresultcallback) | 以指定顏色突顯樣本文本的所有匹配項目。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_slide_by_id/#int) | 依 Id 取得 Slide、MasterSlide 或 LayoutSlide。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/presentation/join_portions_with_same_formatting/#) | 在所有投影片的所有可接受圖形中的所有段落合併格式相同的 Run。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_regex/#str-asposeslidescolor) | 以指定顏色突顯正則表達式的所有匹配項目。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) | 將所有指定文字的出現替換為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/presentation/replace_regex/#str-str) | 將正則表達式的所有匹配項目替換為指定字串。 |

### 參見
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)