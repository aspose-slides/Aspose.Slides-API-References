---
title: IPresentation
second_title: Aspose.Sildes for .NET API 參考文件
description: 簡報文件
type: docs
weight: 6750
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
| [AllCustomXmlParts](../../aspose.slides/ipresentation/allcustomxmlparts) { get; } | 返回簡報中的所有自訂資料部件。唯讀 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [AsIDisposable](../../aspose.slides/ipresentation/asidisposable) { get; } | 返回 IDisposable 介面。唯讀 IDisposable。 |
| [AsIPresentationComponent](../../aspose.slides/ipresentation/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../ipresentationcomponent)。 |
| [Audios](../../aspose.slides/ipresentation/audios) { get; } | 返回簡報中所有嵌入式音訊檔案的集合。唯讀 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/ipresentation/commentauthors) { get; } | 返回評論作者的集合。唯讀 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/ipresentation/currentdatetime) { get; set; } | 返回或設定用於取代日期時間欄位內容的日期與時間。預設為此 Presentation 物件建立的時間。可讀寫 DateTime。 |
| [CustomData](../../aspose.slides/ipresentation/customdata) { get; } | 返回簡報的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/ipresentation/defaulttextstyle) { get; } | 返回形狀的預設文字樣式。唯讀 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/ipresentation/digitalsignatures) { get; } | 返回用於簽署簡報的簽名集合。唯讀 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/ipresentation/documentproperties) { get; } | 返回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/ipresentation/firstslidenumber) { get; set; } | 表示簡報中的第一張投影片編號。可讀寫 Int32。 |
| [FontsManager](../../aspose.slides/ipresentation/fontsmanager) { get; } | 返回字型管理器。唯讀 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/ipresentation/headerfootermanager) { get; } | 返回簡報的頁首頁尾管理器。唯讀 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/ipresentation/hyperlinkqueries) { get; } | 提供對所有簡報投影片（不含母片、版面配置、備註投影片）內超連結的便利存取。唯讀 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/ipresentation/images) { get; } | 返回簡報中所有影像的集合。唯讀 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/ipresentation/layoutslides) { get; } | 返回簡報中定義的所有版面投影片清單。唯讀 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/ipresentation/masterhandoutslidemanager) { get; } | 返回講義母片管理器。唯讀 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/ipresentation/masternotesslidemanager) { get; } | 返回備註母片管理器。唯讀 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/ipresentation/masters) { get; } | 返回簡報中定義的所有母片投影片清單。唯讀 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/ipresentation/mastertheme) { get; } | 返回簡報的母片主題。唯讀 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/ipresentation/notessize) { get; } | 返回備註投影片尺寸物件。唯讀 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/ipresentation/protectionmanager) { get; } | 取得此簡報的權限管理器。唯讀 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/ipresentation/sections) { get; } | 返回簡報中定義的所有投影片區段清單。唯讀 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/ipresentation/sensitivitylabels) { get; } | 返回套用於簡報文件的敏感度標籤集合。唯讀 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/ipresentation/slides) { get; } | 返回簡報中定義的所有投影片清單。唯讀 [`ISlideCollection`](../islidecollection)。 |
| [SlideSize](../../aspose.slides/ipresentation/slidesize) { get; } | 返回投影片尺寸物件。唯讀 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/ipresentation/sourceformat) { get; } | 返回簡報載入時的來源格式資訊。唯讀 [`SourceFormat`](./sourceformat)。 |
| [VbaProject](../../aspose.slides/ipresentation/vbaproject) { get; set; } | 取得含有簡報巨集的 VBA 專案。可讀寫 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/ipresentation/videos) { get; } | 返回簡報中所有嵌入式影片檔案的集合。唯讀 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/ipresentation/viewproperties) { get; } | 取得簡報範圍的視圖屬性。唯讀 [`IViewProperties`](../iviewproperties)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages)(IRenderingOptions) | 返回簡報所有投影片的縮圖影像物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_1)(IRenderingOptions, int[]) | 返回指定投影片的縮圖位圖物件。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_5)(IRenderingOptions, Size) | 返回簡報所有投影片的縮圖影像物件，使用指定大小。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_4)(IRenderingOptions, float, float) | 返回簡報所有投影片的縮圖影像物件，使用自訂縮放。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 返回指定投影片的縮圖影像物件，使用指定大小。 |
| [GetImages](../../aspose.slides/ipresentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 返回指定投影片的縮圖影像物件，使用自訂縮放。 |
| [GetSlideById](../../aspose.slides/ipresentation/getslidebyid)(uint) | 根據 Id 返回 Slide、MasterSlide 或 LayoutSlide。 |
| [HighlightRegex](../../aspose.slides/ipresentation/highlightregex)(Regex, Color, IFindResultCallback) | 以指定顏色突顯正則表達式的全部匹配項目。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext)(string, Color) | 以指定顏色突顯樣本文字的全部匹配項目。 |
| [HighlightText](../../aspose.slides/ipresentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 以指定顏色突顯樣本文字的全部匹配項目。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/ipresentation/joinportionswithsameformatting)() | 在所有投影片的所有可接受形狀的所有段落中，合併具有相同格式的文字片段。 |
| [ReplaceRegex](../../aspose.slides/ipresentation/replaceregex)(Regex, string, IFindResultCallback) | 將正則表達式的全部匹配項目替換為指定字串。 |
| [ReplaceText](../../aspose.slides/ipresentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 將指定文字的全部出現處替換為另一指定文字。 |
| [Save](../../aspose.slides/ipresentation/save#save)(IXamlOptions) | 將簡報的所有投影片儲存為代表 XAML 標記的一組檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_1)(Stream, SaveFormat) | 以指定格式將簡報的所有投影片儲存至串流。 |
| [Save](../../aspose.slides/ipresentation/save#save_5)(string, SaveFormat) | 以指定格式將簡報的所有投影片儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_3)(Stream, int[], SaveFormat) | 以指定格式將簡報的指定投影片儲存至串流。 |
| [Save](../../aspose.slides/ipresentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 以指定格式及其他選項將簡報的所有投影片儲存至串流。 |
| [Save](../../aspose.slides/ipresentation/save#save_7)(string, int[], SaveFormat) | 以指定格式將簡報的指定投影片儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_6)(string, SaveFormat, ISaveOptions) | 以指定格式及其他選項將簡報的所有投影片儲存至檔案。 |
| [Save](../../aspose.slides/ipresentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 以指定格式及其他選項將簡報的指定投影片儲存至串流。 |
| [Save](../../aspose.slides/ipresentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 以指定格式及其他選項將簡報的指定投影片儲存至檔案。 |

### 另請參閱

* 介面 [IPresentationComponent](../ipresentationcomponent)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->