---
title: PdfOptions
second_title: Aspose.Slides for C++ API 參考文件
description: 提供控制簡報以 Pdf 格式儲存的選項。
type: docs
weight: 573
url: /zh-hant/aspose.slides.export/pdfoptions/
---
## PdfOptions 類別

提供控制簡報以 Pdf 格式儲存的選項。

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## 方法

| Method | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | 包含一組旗標，用於指定文件以使用者權限開啟時應授予的存取權限。請參見 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | 傳回字體族的使用者自訂名稱陣列，[Aspose.Slides](../../aspose.slides/) 應將其視為共用。讀取 [System::String](../../system/string/)[]。 |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | 如果 **true**，則將指定的透明色彩套用到影像。 |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | 指示是否應自動為每張影像選取最有效的壓縮（而非預設壓縮）。若設定為 **bool**.true，簡報中的每張影像將選擇最適當的壓縮演算法，從而產生較小的 PDF 文件。 |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | 產生的 PDF 文件之期望符合等級。讀取 [PdfCompliance](../pdfcompliance/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 傳回在找不到來源字體時使用的字體。讀取 [System::String](../../system/string/)。 |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | 若為 **bool**.true，則在每張投影片周圍繪製黑色框線。讀取 **bool**。 |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | 決定是否應嵌入字體的全部字元或僅使用子集。讀取 **bool**。 |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | 決定 [Aspose.Slides](../../aspose.slides/) 是否會為 ASCII（33..127 代碼範圍）文字嵌入常用字體。[Fonts](../../aspose.slides/fonts/) 對於大於 127 的字元代碼總是會嵌入。常用字體清單包括 PDF 的基本 14 種字體以及使用者指定的其他字體。讀取 **bool**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 傳回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | 取得影像的透明色彩。 |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | 若為 **bool**.true，則將簡報中的所有 OLE 資料轉換為嵌入於產生的 PDF 中的檔案。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制匯出文件中 [Ink](../../aspose.slides.ink/) 物件外觀的選項。唯讀 [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | 傳回決定 PDF 中 JPEG 圖像品質的值。讀取 **uint8_t**。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | 設定使用者密碼以保護 PDF 文件。讀取 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 代表以百分比儲存進度更新的回呼物件。請參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | 指示當字體不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存至 PDF。此方法可提升特定字體於產生的 PDF 中的文字品質。讀取 **bool**。 |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | 若為 **bool**.true，則將簡報中使用的所有圖元檔案轉換為 PNG 圖像。讀取 **bool**。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 取得匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時投影片在頁面上的排列模式。 |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | 傳回決定 PDF 中影像解析度的值。 |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | 指定文件中所有文字內容使用的壓縮類型。讀取 [PdfTextCompression](../pdftextcompression/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或設定一個接收警告並決定載入程序是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的型別實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定機制。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
|  [PdfOptions](./pdfoptions/)() | 預設建構子。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值遞減共享參考計數。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | 包含一組旗標，用於指定文件以使用者權限開啟時應授予的存取權限。請參見 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | 設定字體族的使用者自訂名稱陣列，[Aspose.Slides](../../aspose.slides/) 應將其視為共用。寫入 [System::String](../../system/string/)[]。 |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | 如果 **true**，則將指定的透明色彩套用到影像。 |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | 指示是否應自動為每張影像選取最有效的壓縮（而非預設壓縮）。若設定為 **bool**.true，簡報中的每張影像將選擇最適當的壓縮演算法，從而產生較小的 PDF 文件。 |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | 產生的 PDF 文件之期望符合等級。寫入 [PdfCompliance](../pdfcompliance/)。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 設定在找不到來源字體時使用的字體。寫入 [System::String](../../system/string/)。 |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | 若為 **bool**.true，則在每張投影片周圍繪製黑色框線。寫入 **bool**。 |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | 決定是否應嵌入字體的全部字元或僅使用子集。寫入 **bool**。 |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | 決定 [Aspose.Slides](../../aspose.slides/) 是否會為 ASCII（33..127 代碼範圍）文字嵌入常用字體。[Fonts](../../aspose.slides/fonts/) 對於大於 127 的字元代碼總是會嵌入。常用字體清單包括 PDF 的基本 14 種字體以及使用者指定的其他字體。寫入 **bool**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | 設定影像的透明色彩。 |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | 若為 **bool**.true，則將簡報中的所有 OLE 資料轉換為嵌入於產生的 PDF 中的檔案。寫入 **bool**。 |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | 設定決定 PDF 中 JPEG 圖像品質的值。寫入 **uint8_t**。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | 設定使用者密碼以保護 PDF 文件。寫入 [System::String](../../system/string/)。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 代表以百分比儲存進度更新的回呼物件。請參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | 指示當字體不支援粗體樣式時，文字是否應以點陣圖方式光柵化並儲存至 PDF。此方法可提升特定字體於產生的 PDF 中的文字品質。寫入 **bool**。 |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | 若為 **bool**.true，則將簡報中使用的所有圖元檔案轉換為 PNG 圖像。寫入 **bool**。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 設定匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時投影片在頁面上的排列模式。 |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | 設定決定 PDF 中影像解析度的值。 |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | 指定文件中所有文字內容使用的壓縮類型。寫入 [PdfTextCompression](../pdftextcompression/)。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或設定一個接收警告並決定載入程序是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖機制。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

以下範例示範如何使用自訂選項將 PowerPoint 轉換為 PDF。  
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// 實例化 PdfOptions 類別
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 設定 JPEG 品質
pdfOptions->set_JpegQuality(90);
// 設定圖元檔案的行為
pdfOptions->set_SaveMetafilesAsPng(true);
// 設定文字壓縮等級
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// 定義 PDF 標準
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// 將簡報儲存為 PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```

以下範例示範如何將 PowerPoint 轉換為包含隱藏投影片的 PDF。  
```cpp
// 實例化一個表示 PowerPoint 檔案的 Presentation 類別
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// 實例化 PdfOptions 類別
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 新增隱藏投影片
pdfOptions->set_ShowHiddenSlides(true);
// 將簡報儲存為 PDF
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```

以下範例示範如何將 PowerPoint 轉換為受密碼保護的 PDF。  
```cpp
// 實例化一個表示 PowerPoint 檔案的 Presentation 物件
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// 設定 PDF 密碼和存取權限
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// 將簡報儲存為 PDF
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```

以下範例示範如何將 PowerPoint 轉換為含備註的 PDF。  
```cpp
// 實例化一個表示簡報檔案的 Presentation 物件
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## 參見

* 類別 [SaveOptions](../saveoptions/)
* 類別 [IPdfOptions](../ipdfoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 程式庫 [Aspose.Slides](../../)