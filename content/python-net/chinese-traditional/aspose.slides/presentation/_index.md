---
title: Presentation class
second_title: Aspose.Slides for Python via .NET API 參考手冊
description: 
type: docs
url: /zh-hant/aspose.slides/presentation/
---
## Presentation 類別

代表 Microsoft PowerPoint 簡報。

Presentation 類型公開以下成員：

## 建構函式

| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#) | 此建構函式從頭建立新的簡報。<br/>            建立的簡報包含一張空白投影片。 |
| [`__init__(self, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#loadoptions) | 此建構函式從頭建立新的簡報。<br/>            建立的簡報包含一張空白投影片。 |
| [`__init__(self, stream)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#iorawiobase) | 此建構函式是讀取既有 Presentation 的主要機制。 |
| [`__init__(self, stream, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#iorawiobase-loadoptions) | 此建構函式是讀取既有 Presentation 的主要機制。 |
| [`__init__(self, file)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#str) | 此建構函式取得來源檔案路徑，從中讀取 Presentation 的內容。 |
| [`__init__(self, file, load_options)`](/slides/python-net/zh-hant/aspose.slides/presentation/__init__/#str-loadoptions) | 此建構函式取得來源檔案路徑，從中讀取 Presentation 的內容。 |

## 屬性

| Property | Description |
| :- | :- |
| [`current_date_time`](/slides/python-net/zh-hant/aspose.slides/presentation/current_date_time/) | 傳回或設定用於取代 datetime 欄位內容的日期與時間。<br/>            預設為此 Presentation 物件建立的時間。<br/>            讀寫 **System.DateTime**. |
| [`header_footer_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/header_footer_manager/) | 傳回實際的 HeaderFooter 管理器。<br/>            唯讀 [`IPresentationHeaderFooterManager`](/slides/python-net/zh-hant/aspose.slides/ipresentationheaderfootermanager). |
| [`protection_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/protection_manager/) | 取得此簡報的權限管理器。<br/>            唯讀 [`IProtectionManager`](/slides/python-net/zh-hant/aspose.slides/iprotectionmanager). |
| [`slides`](/slides/python-net/zh-hant/aspose.slides/presentation/slides/) | 傳回簡報中定義的所有投影片清單。<br/zh-hant/>            唯讀 [`ISlideCollection`](/slides/python-net/zh-hant/aspose.slides/islidecollection). |
| [`sections`](/slides/python-net/zh-hant/aspose.slides/presentation/sections/) | 傳回簡報中定義的所有投影片分節清單。<br/>            唯讀 [`ISectionCollection`](/slides/python-net/zh-hant/aspose.slides/isectioncollection). |
| [`slide_size`](/slides/python-net/zh-hant/aspose.slides/presentation/slide_size/) | 傳回投影片尺寸物件。<br/>            唯讀 [`ISlideSize`](/slides/python-net/zh-hant/aspose.slides/islidesize). |
| [`notes_size`](/slides/python-net/zh-hant/aspose.slides/presentation/notes_size/) | 傳回備註投影片尺寸物件。<br/>            唯讀 [`INotesSize`](/slides/python-net/zh-hant/aspose.slides/inotessize). |
| [`layout_slides`](/slides/python-net/zh-hant/aspose.slides/presentation/layout_slides/) | 傳回簡報中定義的所有版面配置投影片清單。<br/>            唯讀 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh-hant/aspose.slides/igloballayoutslidecollection). |
| [`masters`](/slides/python-net/zh-hant/aspose.slides/presentation/masters/) | 傳回簡報中定義的所有母片投影片清單。<br/>            唯讀 [`IMasterSlideCollection`](/slides/python-net/zh-hant/aspose.slides/imasterslidecollection). |
| [`master_notes_slide_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/master_notes_slide_manager/) | 傳回備註母片管理器。<br/>            唯讀 [`IMasterNotesSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasternotesslidemanager). |
| [`master_handout_slide_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/master_handout_slide_manager/) | 傳回講義母片管理器。<br/>            唯讀 [`IMasterHandoutSlideManager`](/slides/python-net/zh-hant/aspose.slides/imasterhandoutslidemanager). |
| [`fonts_manager`](/slides/python-net/zh-hant/aspose.slides/presentation/fonts_manager/) | 傳回字型管理器。<br/>            唯讀 [`IFontsManager`](/slides/python-net/zh-hant/aspose.slides/ifontsmanager). |
| [`default_text_style`](/slides/python-net/zh-hant/aspose.slides/presentation/default_text_style/) | 傳回形狀的預設文字樣式。<br/>            唯讀 [`ITextStyle`](/slides/python-net/zh-hant/aspose.slides/itextstyle). |
| [`comment_authors`](/slides/python-net/zh-hant/aspose.slides/presentation/comment_authors/) | 傳回評論作者的集合。<br/>            唯讀 [`ICommentAuthorCollection`](/slides/python-net/zh-hant/aspose.slides/icommentauthorcollection). |
| [`document_properties`](/slides/python-net/zh-hant/aspose.slides/presentation/document_properties/) | 傳回 DocumentProperties 物件，內含標準與自訂文件屬性。<br/>            唯讀 [`IDocumentProperties`](/slides/python-net/zh-hant/aspose.slides/idocumentproperties). |
| [`images`](/slides/python-net/zh-hant/aspose.slides/presentation/images/) | 傳回簡報中所有影像的集合。<br/>            唯讀 [`IImageCollection`](/slides/python-net/zh-hant/aspose.slides/iimagecollection). |
| [`audios`](/slides/python-net/zh-hant/aspose.slides/presentation/audios/) | 傳回簡報中所有嵌入式音訊檔案的集合。<br/>            唯讀 [`IAudioCollection`](/slides/python-net/zh-hant/aspose.slides/iaudiocollection). |
| [`videos`](/slides/python-net/zh-hant/aspose.slides/presentation/videos/) | 傳回簡報中所有嵌入式視訊檔案的集合。<br/>            唯讀 [`IVideoCollection`](/slides/python-net/zh-hant/aspose.slides/ivideocollection). |
| [`slide_show_settings`](/slides/python-net/zh-hant/aspose.slides/presentation/slide_show_settings/) | 傳回簡報的投影片放映設定。 |
| [`digital_signatures`](/slides/python-net/zh-hant/aspose.slides/presentation/digital_signatures/) | 傳回用於簽署簡報的簽章集合。<br/>            唯讀 [`IDigitalSignatureCollection`](/slides/python-net/zh-hant/aspose.slides/idigitalsignaturecollection). |
| [`custom_data`](/slides/python-net/zh-hant/aspose.slides/presentation/custom_data/) | 傳回簡報的自訂資料。<br/>            唯讀 [`ICustomData`](/slides/python-net/zh-hant/aspose.slides/icustomdata). |
| [`all_custom_xml_parts`](/slides/python-net/zh-hant/aspose.slides/presentation/all_custom_xml_parts/) | 傳回簡報中所有自訂資料部件。<br/>            唯讀 [`ICustomXmlPart`](/slides/python-net/zh-hant/aspose.slides/icustomxmlpart)[]. |
| [`vba_project`](/slides/python-net/zh-hant/aspose.slides/presentation/vba_project/) | 取得或設定含有簡報巨集的 VBA 專案。<br/>            讀寫 [`IVbaProject`](/slides/python-net/zh-hant/aspose.slides.vba/ivbaproject). |
| [`hyperlink_queries`](/slides/python-net/zh-hant/aspose.slides/presentation/hyperlink_queries/) | 提供對所有簡報投影片（不含母片、版面配置、備註投影片）中超連結的簡易存取。<br/>            唯讀 [`IHyperlinkQueries`](/slides/python-net/zh-hant/aspose.slides/ihyperlinkqueries). |
| [`view_properties`](/slides/python-net/zh-hant/aspose.slides/presentation/view_properties/) | 取得簡報範圍的檢視屬性。<br/>            唯讀 [`IViewProperties`](/slides/python-net/zh-hant/aspose.slides/iviewproperties). |
| [`first_slide_number`](/slides/python-net/zh-hant/aspose.slides/presentation/first_slide_number/) | 表示簡報中的第一張投影片編號 |
| [`sensitivity_labels`](/slides/python-net/zh-hant/aspose.slides/presentation/sensitivity_labels/) | 傳回套用於簡報文件的敏感度標籤集合。<br/>            唯讀 [`ISensitivityLabelCollection`](/slides/python-net/zh-hant/aspose.slides/isensitivitylabelcollection). |
| [`source_format`](/slides/python-net/zh-hant/aspose.slides/presentation/source_format/) | 傳回簡報載入時所使用的格式資訊。<br/>            唯讀 [`SourceFormat`](/slides/python-net/zh-hant/aspose.slides/sourceformat). |
| [`master_theme`](/slides/python-net/zh-hant/aspose.slides/presentation/master_theme/) | 傳回母片佈景主題。<br/>            唯讀 [`IMasterTheme`](/slides/python-net/zh-hant/aspose.slides.theme/imastertheme). |
| [`presentation`](/slides/python-net/zh-hant/aspose.slides/presentation/presentation/) |  |

## 方法

| Method | Description |
| :- | :- |
| [`save(self, fname, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat) | 將簡報的所有投影片儲存為指定格式的檔案。 |
| [`save(self, stream, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat) | 將簡報的所有投影片以指定格式儲存至資料流。 |
| [`save(self, fname, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |  |
| [`save(self, stream, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) | 將簡報的所有投影片以指定格式及額外選項儲存至資料流。 |
| [`save(self, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#asposeslidesexportxamlixamloptions) | 將簡報的所有投影片儲存為一組表示 XAML 標記的檔案。 |
| [`save(self, fname, slides, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat) |將簡報中指定的投影片儲存為指定格式的檔案，保留頁碼。 |
| [`save(self, fname, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |將簡報中指定的投影片儲存為指定格式的檔案，保留頁碼。 |
| [`save(self, stream, slides, format)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat) |將簡報中指定的投影片以指定格式儲存至資料流，保留頁碼。 |
| [`save(self, stream, slides, format, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/save/#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions) |將簡報中指定的投影片以指定格式儲存至資料流，保留頁碼。 |
| [`get_images(self, options)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions) |傳回簡報所有投影片的 Image 物件。 |
| [`get_images(self, options, slides)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint) |傳回簡報中指定投影片的縮圖 Image 物件。 |
| [`get_images(self, options, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-float-float) |傳回簡報所有投影片的縮圖 Image 物件，使用自訂縮放。 |
| [`get_images(self, options, slides, scale_x, scale_y)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-float-float) |傳回簡報中指定投影片的縮圖 Image 物件，使用自訂縮放。 |
| [`get_images(self, options, image_size)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-asposepydrawingsize) |傳回簡報所有投影片的縮圖 Image 物件，使用指定尺寸。 |
| [`get_images(self, options, slides, image_size)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_images/#asposeslidesexportirenderingoptions-listint-asposepydrawingsize) |傳回簡報中指定投影片的縮圖 Image 物件，使用指定尺寸。 |
| [`highlight_text(self, text, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor) |以指定顏色突顯樣本文字的所有匹配項。 |
| [`highlight_text(self, text, highlight_color, options, callback)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_text/#str-asposepydrawingcolor-itextsearchoptions-ifindresultcallback) |以指定顏色突顯樣本文字的所有匹配項。 |
| [`get_slide_by_id(self, id)`](/slides/python-net/zh-hant/aspose.slides/presentation/get_slide_by_id/#int) |依 Id 傳回 Slide、MasterSlide 或 LayoutSlide。 |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/zh-hant/aspose.slides/presentation/join_portions_with_same_formatting/#) |將所有投影片中所有可接受形狀的段落中，格式相同的文字片段合併。 |
| [`highlight_regex(self, regex, highlight_color)`](/slides/python-net/zh-hant/aspose.slides/presentation/highlight_regex/#str-asposepydrawingcolor) |以指定顏色突顯正規表示式的所有匹配項。 |
| [`replace_text(self, old_text, new_text, options, callback)`](/slides/python-net/zh-hant/aspose.slides/presentation/replace_text/#str-str-itextsearchoptions-ifindresultcallback) |將所有出現的指定文字替換為另一個指定文字。 |
| [`replace_regex(self, regex, new_text)`](/slides/python-net/zh-hant/aspose.slides/presentation/replace_regex/#str-str) |將正規表示式的所有匹配項替換為指定的字串。 |


### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)