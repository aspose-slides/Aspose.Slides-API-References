---
title: Presentation
second_title: Aspose.Sildes for .NET API 參考
description: 代表 Microsoft PowerPoint 簡報。
type: docs
weight: 9590
url: /zh-hant/aspose.slides/presentation/
---
## Presentation 類別

代表 Microsoft PowerPoint 簡報。

```csharp
public sealed class Presentation : IPresentation
```

## 建構函式

| 名稱 | 說明 |
| --- | --- |
| [Presentation](presentation#constructor)() | 此建構函式從頭建立新的簡報。建立的簡報包含一個空白投影片。 |
| [Presentation](presentation#constructor_1)(LoadOptions) | 此建構函式從頭建立新的簡報。建立的簡報包含一個空白投影片。 |
| [Presentation](presentation#constructor_2)(Stream) | 此建構函式是讀取現有 Presentation 的主要機制。 |
| [Presentation](presentation#constructor_4)(string) | 此建構函式取得要讀取 Presentation 內容的來源檔案路徑。 |
| [Presentation](presentation#constructor_3)(Stream, LoadOptions) | 此建構函式是讀取現有 Presentation 的主要機制。 |
| [Presentation](presentation#constructor_5)(string, LoadOptions) | 此建構函式取得要讀取 Presentation 內容的來源檔案路徑。 |

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AllCustomXmlParts](../../aspose.slides/presentation/allcustomxmlparts) { get; } | 傳回簡報中所有自訂資料部件。唯讀 [`ICustomXmlPart`](../icustomxmlpart)[]. |
| [Audios](../../aspose.slides/presentation/audios) { get; } | 傳回簡報中所有嵌入式音訊檔案的集合。唯讀 [`IAudioCollection`](../iaudiocollection). |
| [CommentAuthors](../../aspose.slides/presentation/commentauthors) { get; } | 傳回評論作者的集合。唯讀 [`ICommentAuthorCollection`](../icommentauthorcollection). |
| [CurrentDateTime](../../aspose.slides/presentation/currentdatetime) { get; set; } | 取得或設定將取代日期時間欄位內容的日期與時間。預設為此 Presentation 物件建立的時間。可讀寫 DateTime. |
| [CustomData](../../aspose.slides/presentation/customdata) { get; } | 傳回簡報的自訂資料。唯讀 [`ICustomData`](../icustomdata). |
| [DefaultTextStyle](../../aspose.slides/presentation/defaulttextstyle) { get; } | 傳回形狀的預設文字樣式。唯讀 [`ITextStyle`](../itextstyle). |
| [DigitalSignatures](../../aspose.slides/presentation/digitalsignatures) { get; } | 傳回用於簽署簡報的簽章集合。唯讀 [`IDigitalSignatureCollection`](../idigitalsignaturecollection). |
| [DocumentProperties](../../aspose.slides/presentation/documentproperties) { get; } | 傳回包含標準與自訂文件屬性的 DocumentProperties 物件。唯讀 [`IDocumentProperties`](../idocumentproperties). |
| [FirstSlideNumber](../../aspose.slides/presentation/firstslidenumber) { get; set; } | 代表簡報中第一張投影片的編號。 |
| [FontsManager](../../aspose.slides/presentation/fontsmanager) { get; } | 傳回字型管理器。唯讀 [`IFontsManager`](../ifontsmanager). |
| [HeaderFooterManager](../../aspose.slides/presentation/headerfootermanager) { get; } | 傳回實際的頁首/頁尾管理器。唯讀 [`IPresentationHeaderFooterManager`](../ipresentationheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/presentation/hyperlinkqueries) { get; } | 提供簡易存取所有簡報投影片中包含的超連結（不含母片、版面配置、備註投影片）。唯讀 [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [Images](../../aspose.slides/presentation/images) { get; } | 傳回簡報中所有圖像的集合。唯讀 [`IImageCollection`](../iimagecollection). |
| [LayoutSlides](../../aspose.slides/presentation/layoutslides) { get; } | 傳回簡報中定義的所有版面投影片清單。唯讀 [`IGlobalLayoutSlideCollection`](../igloballayoutslidecollection). |
| [MasterHandoutSlideManager](../../aspose.slides/presentation/masterhandoutslidemanager) { get; } | 傳回講義母片管理器。唯讀 [`IMasterHandoutSlideManager`](../imasterhandoutslidemanager). |
| [MasterNotesSlideManager](../../aspose.slides/presentation/masternotesslidemanager) { get; } | 傳回備註母片管理器。唯讀 [`IMasterNotesSlideManager`](../imasternotesslidemanager). |
| [Masters](../../aspose.slides/presentation/masters) { get; } | 傳回簡報中定義的所有母片投影片清單。唯讀 [`IMasterSlideCollection`](../imasterslidecollection). |
| [MasterTheme](../../aspose.slides/presentation/mastertheme) { get; } | 傳回母片主題。唯讀 [`IMasterTheme`](../../aspose.slides.theme/imastertheme). |
| [NotesSize](../../aspose.slides/presentation/notessize) { get; } | 傳回備註投影片大小物件。唯讀 [`INotesSize`](../inotessize). |
| [ProtectionManager](../../aspose.slides/presentation/protectionmanager) { get; } | 取得此簡報的權限管理器。唯讀 [`IProtectionManager`](../iprotectionmanager). |
| [Sections](../../aspose.slides/presentation/sections) { get; } | 傳回簡報中定義的所有投影片分節清單。唯讀 [`ISectionCollection`](../isectioncollection). |
| [SensitivityLabels](../../aspose.slides/presentation/sensitivitylabels) { get; } | 傳回套用於簡報文件的敏感度標籤集合。唯讀 [`ISensitivityLabelCollection`](../isensitivitylabelcollection). |
| [Slides](../../aspose.slides/presentation/slides) { get; } | 傳回簡報中定義的所有投影片清單。唯讀 [`ISlideCollection`](../islidecollection). |
| [SlideShowSettings](../../aspose.slides/presentation/slideshowsettings) { get; } | 傳回簡報的投影片放映設定。 |
| [SlideSize](../../aspose.slides/presentation/slidesize) { get; } | 傳回投影片大小物件。唯讀 [`ISlideSize`](../islidesize). |
| [SourceFormat](../../aspose.slides/presentation/sourceformat) { get; } | 傳回簡報載入之格式資訊。唯讀 [`SourceFormat`](../sourceformat). |
| [VbaProject](../../aspose.slides/presentation/vbaproject) { get; set; } | 取得或設定含有簡報巨集的 VBA 專案。可讀寫 [`IVbaProject`](../../aspose.slides.vba/ivbaproject). |
| [Videos](../../aspose.slides/presentation/videos) { get; } | 傳回簡報中所有嵌入式影片檔案的集合。唯讀 [`IVideoCollection`](../ivideocollection). |
| [ViewProperties](../../aspose.slides/presentation/viewproperties) { get; } | 取得簡報全域檢視屬性。唯讀 [`IViewProperties`](../iviewproperties). |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Dispose](../../aspose.slides/presentation/dispose)() | 釋放此 Presentation 物件使用的所有資源。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages)(IRenderingOptions) | 傳回簡報所有投影片的 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_1)(IRenderingOptions, int[]) | 傳回指定投影片的縮圖 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_5)(IRenderingOptions, Size) | 傳回指定大小的簡報所有投影片的縮圖 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_4)(IRenderingOptions, float, float) | 傳回使用自訂比例的簡報所有投影片的縮圖 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_3)(IRenderingOptions, int[], Size) | 傳回指定投影片，指定大小的縮圖 Image 物件。 |
| [GetImages](../../aspose.slides/presentation/getimages#getimages_2)(IRenderingOptions, int[], float, float) | 傳回指定投影片，使用自訂比例的縮圖 Image 物件。 |
| [GetSlideById](../../aspose.slides/presentation/getslidebyid)(uint) | 依 Id 傳回 Slide、MasterSlide 或 LayoutSlide。 |
| [HighlightRegex](../../aspose.slides/presentation/highlightregex)(Regex, Color, IFindResultCallback) | 使用指定的顏色突顯正則表達式的所有符合項目。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext)(string, Color) | 使用指定的顏色突顯樣本文本的所有符合項目。 |
| [HighlightText](../../aspose.slides/presentation/highlighttext#highlighttext_1)(string, Color, ITextSearchOptions, IFindResultCallback) | 使用指定的顏色突顯樣本文本的所有符合項目。 |
| [JoinPortionsWithSameFormatting](../../aspose.slides/presentation/joinportionswithsameformatting)() | 合併所有投影片中所有可接受形狀之所有段落中具有相同格式的 Run。 |
| [ReplaceRegex](../../aspose.slides/presentation/replaceregex)(Regex, string, IFindResultCallback) | 將正則表達式的所有符合項目取代為指定的字串。 |
| [ReplaceText](../../aspose.slides/presentation/replacetext)(string, string, ITextSearchOptions, IFindResultCallback) | 將指定文字的所有出現取代為另一個指定文字。 |
| [Save](../../aspose.slides/presentation/save#save)(IXamlOptions) | 將簡報的所有投影片儲存為代表 XAML 標記的一組檔案。 |
| [Save](../../aspose.slides/presentation/save#save_1)(Stream, SaveFormat) | 將簡報的所有投影片以指定格式儲存至串流。 |
| [Save](../../aspose.slides/presentation/save#save_5)(string, SaveFormat) | 將簡報的所有投影片以指定格式儲存至檔案。 |
| [Save](../../aspose.slides/presentation/save#save_3)(Stream, int[], SaveFormat) | 將簡報的指定投影片以指定格式、保留頁碼儲存至串流。 |
| [Save](../../aspose.slides/presentation/save#save_2)(Stream, SaveFormat, ISaveOptions) | 將簡報的所有投影片以指定格式及額外選項儲存至串流。 |
| [Save](../../aspose.slides/presentation/save#save_7)(string, int[], SaveFormat) | 將簡報的指定投影片以指定格式、保留頁碼儲存至檔案。 |
| [Save](../../aspose.slides/presentation/save#save_6)(string, SaveFormat, ISaveOptions) |  |
| [Save](../../aspose.slides/presentation/save#save_4)(Stream, int[], SaveFormat, ISaveOptions) | 將簡報的指定投影片以指定格式、保留頁碼，並使用 ISaveOptions 儲存至串流。 |
| [Save](../../aspose.slides/presentation/save#save_8)(string, int[], SaveFormat, ISaveOptions) | 將簡報的指定投影片以指定格式、保留頁碼，並使用 ISaveOptions 儲存至檔案。 |

### 範例

以下範例說明如何建立 PowerPoint 簡報。

```csharp
[C#]
// 實例化一個代表簡報檔案的 Presentation 物件
using (Presentation presentation = new Presentation())
{
    // 取得第一張投影片
    ISlide slide = presentation.Slides[0];
    // 新增類型為線條的自動形狀
    slide.Shapes.AddAutoShape(ShapeType.Line, 50, 150, 300, 0);
	// 儲存簡報檔案。
    presentation.Save("NewPresentation_out.pptx", SaveFormat.Pptx);
}
```

以下範例說明如何開啟與儲存簡報。

```csharp
[C#]
// 載入任何受支援的簡報檔案，例如 ppt、pptx、odp 等。
using (Presentation presentation = new Presentation("Sample.odp"))
{
	// 儲存簡報檔案。
	presentation.Save("OutputPresenation.pptx", SaveFormat.Pptx);
}
```

### 參見

* 介面 [IPresentation](../ipresentation)
* 命名空間 [Aspose.Slides](../../aspose.slides)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->