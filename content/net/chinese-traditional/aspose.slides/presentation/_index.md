---
title: Presentation
second_title: Aspose.Sildes for .NET API 參考文件
description: 代表 Microsoft PowerPoint 簡報。
type: docs
weight: 9610
url: /zh-hant/aspose.slides/presentation/
---
## Presentation 類別

代表 Microsoft PowerPoint 簡報。

```csharp
public sealed class Presentation : IPresentation
```

## 建構函式

| Name | Description |
| --- | --- |
| [Presentation](presentation#constructor)() | 此建構函式會從頭建立新的簡報。建立的簡報包含一張空白投影片。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | 此建構函式會從頭建立新的簡報。建立的簡報包含一張空白投影片。 |
| [Presentation](presentation#constructor_2)(Stream) | 此建構函式是讀取現有 Presentation 的主要機制。 |
| [Presentation](presentation#constructor_4)(string) | 此建構函式取得來源檔案路徑，從該路徑讀取 Presentation 的內容。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | 此建構函式是讀取現有 Presentation 的主要機制。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | 此建構函式取得來源檔案路徑，從該路徑讀取 Presentation 的內容。 |

## 屬性

| Name | Description |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | 傳回簡報中所有自訂資料部分。唯讀 [`ICustomXmlPart`](../icustomxmlpart)[]。 |
| [Audios](../../aspose.slides/presentation/audios) { get; } | 傳回簡報中所有嵌入式音訊檔案的集合。唯讀 [`IAudioCollection`](../iaudiocollection)。 |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | 傳回評論作者的集合。唯讀 [`ICommentAuthorCollection`](../icommentauthorcollection)。 |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 傳回或設定取代 datetime 欄位內容的日期與時間。預設為此 Presentation 物件建立的時間。可讀寫 DateTime。 |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | 傳回簡報的自訂資料。唯讀 [`ICustomData`](../icustomdata)。 |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 傳回圖形的預設文字樣式。唯讀 [`ITextStyle`](../itextstyle)。 |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | 傳回用於簽署簡報的簽章集合。唯讀 [`IDigitalSignatureCollection`](../idigitalsignaturecollection)。 |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 傳回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [`IDocumentProperties`](../idocumentproperties)。 |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | 表示簡報中第一張投影片的編號 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | 傳回字型管理器。唯讀 [`IFontsManager`](../ifontsmanager)。 |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 傳回實際的頁眉頁腳管理器。唯讀 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager)。 |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | 提供對所有簡報投影片（不含母片、版面配置、備註投影片）中超連結的簡易存取。唯讀 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [Images](../../aspose.slides/presentation/images) { get; } | 傳回簡報中所有影像的集合。唯讀 [`IImageCollection`](../iimagecollection)。 |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | 傳回簡報中所有已定義的版面投影片清單。唯讀 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection)。 |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 傳回講義母片管理器。唯讀 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager)。 |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | 傳回備註母片管理器。唯讀 [`IMasterNotesSlideManager`](../imasternotesslidemanager)。 |
| [Masters](../../aspose.slides/presentation/masters) { get; } | 傳回簡報中所有已定義的母片清單。唯讀 [`IMasterSlideCollection`](../imasterslidecollection)。 |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | 傳回母片主題。唯讀 [`IMasterTheme`](../../aspose.slides.theme/imastertheme)。 |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | 傳回備註投影片尺寸物件。唯讀 [`INotesSize`](../inotessize)。 |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | 取得此簡報的權限管理器。唯讀 [`IProtectionManager`](../iprotectionmanager)。 |
| [Sections](../../aspose.slides/presentation/sections) { get; } | 傳回簡報中所有已定義的投影片分節清單。唯讀 [`ISectionCollection`](../isectioncollection)。 |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | 傳回套用於簡報文件的敏感度標籤集合。唯讀 [`ISensitivityLabelCollection`](../isensitivitylabelcollection)。 |
| [Slides](../../aspose.slides/presentation/slides) { get; } | 傳回簡報中所有已定義的投影片清單。唯讀 [`ISlideCollection`](../islidecollection)。 |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | 傳回簡報的投影片播放設定。 |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | 傳回投影片尺寸物件。唯讀 [`ISlideSize`](../islidesize)。 |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | 傳回簡報載入之格式資訊。唯讀 [`SourceFormat`](../sourceformat)。 |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | 取得或設定包含簡報巨集的 VBA 專案。可讀寫 [`IVbaProject`](../../aspose.slides.vba/ivbaproject)。 |
| [Videos](../../aspose.slides/presentation/videos) { get; } | 傳回簡報中所有嵌入式影片檔案的集合。唯讀 [`IVideoCollection`](../ivideocollection)。 |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | 取得簡報全域檢視屬性。唯讀 [`IViewProperties`](../iviewproperties)。 |

## 方法

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | 釋放此 Presentation 物件使用的所有資源。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | 傳回簡報所有投影片的 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 傳回簡報中指定投影片的縮圖 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 傳回簡報所有投影片的縮圖 Image 物件，使用指定的大小。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | 傳回簡報所有投影片的縮圖 Image 物件，使用自訂縮放比例。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 傳回指定投影片的縮圖 Image 物件，使用指定的大小。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 傳回指定投影片的縮圖 Image 物件，使用自訂縮放比例。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | 依 Id 傳回 Slide、MasterSlide 或 LayoutSlide。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 以指定的顏色突顯正規表達式的所有匹配項目。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | 以指定的顏色突顯樣本文字的所有匹配項目。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 以指定的顏色突顯樣本文字的所有匹配項目。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | 在所有投影片的所有可接受圖形的段落中，合併具有相同格式的文字執行序列。 |
| [RefreshChartsData](../../aspose.slides/presentation/refreshchartsdata)(bool) | 從來源活頁簿重新載入簡報中所有圖表的資料。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 以指定的字串取代正規表達式的所有匹配項目。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 將所有指定文字的出現處取代為另一個指定文字。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | 將簡報的所有投影片保存為一組代表 XAML 標記的檔案。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 將簡報的所有投影片以指定格式保存至串流。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 將簡報的所有投影片以指定格式保存至檔案。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 將簡報中指定的投影片以指定格式保存至串流，保留頁碼。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 將簡報的所有投影片以指定格式保存至串流，並使用額外選項。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 將簡報中指定的投影片以指定格式保存至檔案，保留頁碼。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 將簡報中指定的投影片以指定格式保存至串流，保留頁碼。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 將簡報中指定的投影片以指定格式保存至檔案，保留頁碼。 |

### 範例

以下範例示範如何建立 PowerPoint Presentation。

```csharp
[C#]
// 實例化一個代表簡報檔案的 Presentation 物件
using (Presentation presentation = new Presentation())
{
    // 取得第一張投影片
    ISlide slide = presentation.Slides[0];
    // 新增一個類型為 line 的自動圖形
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// 保存簡報檔案。
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

以下範例示範如何開啟與保存 Presentation。

```csharp
[C#]
// 載入 Presentation 中支援的任何檔案，例如 ppt、pptx、odp 等等。
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// 保存簡報檔案。
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### 另請參閱

* 介面 [IPresentation](../ipresentation)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 程式集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->