---
title: IPresentation
second_title: Aspose.Sildes for .NET API 參考文件
description: 簡報文件
type: docs
weight: 6770
url: /zh-hant/aspose.slides/ipresentation/
---
## IPresentation 介面

簡報文件

```csharp
public interface IPresentation : IDisposable, IPresentationComponent
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | 傳回簡報中所有自訂資料部分。唯讀 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | 傳回 IDisposable 介面。唯讀 IDisposable。 |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | 傳回簡報中所有嵌入音訊檔案的集合。唯讀 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | 傳回評論作者的集合。唯讀 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | 傳回或設定將取代日期時間欄位內容的日期與時間。預設為此 Presentation 物件建立的時間。讀寫 DateTime。 |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | 傳回簡報的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | 傳回圖形的預設文字樣式。唯讀 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | 傳回用於簽署簡報的簽名集合。唯讀 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 傳回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | 表示簡報中的第一張投影片編號。讀寫 Int32。 |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | 傳回字型管理器。唯讀 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | 傳回簡報的頁首頁尾管理器。唯讀 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | 提供對所有簡報投影片（不含母投影片、版面配置、備註投影片）中超連結的簡易存取。唯讀 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/ipresentation/images) { get; } | 傳回簡報中所有影像的集合。唯讀 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | 傳回簡報中所有已定義的版面配置投影片清單。唯讀 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | 傳回講義母片管理器。唯讀 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | 傳回備註母片管理器。唯讀 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | 傳回簡報中所有已定義的母投影片清單。唯讀 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | 傳回簡報的母版佈景主題。唯讀 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | 傳回備註投影片大小物件。唯讀 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | 取得此簡報的權限管理器。唯讀 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | 傳回簡報中所有已定義的投影片區段清單。唯讀 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | 傳回套用於簡報文件的敏感度標籤集合。唯讀 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | 傳回簡報中所有已定義的投影片清單。唯讀 [`ISlideCollection`](../islidecollection)。 |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | 傳回投影片大小物件。唯讀 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | 傳回簡報載入之檔案格式資訊。唯讀 [`SourceFormat`](./sourceformat)。 |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | 取得含有簡報巨集的 VBA 專案。讀寫 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | 傳回簡報中所有嵌入的視訊檔案集合。唯讀 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | 取得簡報全域檢視屬性。唯讀 [`IViewProperties`](../iviewproperties)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | 傳回簡報所有投影片的縮圖圖像物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 傳回簡報指定投影片的縮圖 Bitmap 物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 傳回簡報所有投影片，且使用指定大小的縮圖圖像物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | 傳回簡報所有投影片，使用自訂縮放比例的縮圖圖像物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 傳回簡報指定投影片，且使用指定大小的縮圖圖像物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 傳回簡報指定投影片，使用自訂縮放比例的縮圖圖像物件。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | 根據 Id 傳回投影片、母投影片或版面配置投影片。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 使用指定顏色突出顯示正規表達式的所有匹配項。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | 使用指定顏色突出顯示樣本文本的所有匹配項。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 使用指定顏色突出顯示樣本文本的所有匹配項。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | 合併所有投影片中所有可接受圖形內所有段落中具有相同格式的文字執行序。 |
| [RefreshChartsData](../../aspose.slides/ipresentation/refreshchartsdata)(bool) | 從來源活頁簿重新載入簡報中所有圖表的資料。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 將正規表達式的所有匹配項替換為指定字串。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 將指定文字的所有出現替換為另一指定文字。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | 將簡報的所有投影片儲存為一組表示 XAML 標記的檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 將簡報的所有投影片以指定格式儲存至資料流。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 將簡報的所有投影片以指定格式儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 將簡報的指定投影片以指定格式儲存至資料流。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 將簡報的所有投影片以指定格式及額外選項儲存至資料流。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 將簡報的指定投影片以指定格式儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 將簡報的所有投影片以指定格式及額外選項儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 將簡報的指定投影片以指定格式儲存至資料流。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 將簡報的指定投影片以指定格式儲存至檔案。 |

### 另請參閱

* 介面 [IPresentationComponent](../ipresentationcomponent)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->