---
title: IPdfOptions
second_title: Aspose.Slides for C++ API 參考文件
description: 提供控制如何將簡報儲存為 PDF 格式的選項。
type: docs
weight: 274
url: /zh-hant/aspose.slides.export/ipdfoptions/
---
## IPdfOptions 類別

提供控制演示文稿以 PDF 格式儲存方式的選項。

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | 包含一組標誌，指定在以使用者身分開啟文件時應授予的存取權限。見 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | 傳回字體族群的使用者自訂名稱陣列，[Aspose.Slides](../../aspose.slides/) 應視為通用。讀取 [System::String](../../system/string/)[]。 |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | 如果 **true**，則對影像套用指定的透明顏色。 |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | 指示是否應自動為每張影像選擇最有效的壓縮（而非預設）。若設定為 **bool**.true，則會為簡報中的每張影像挑選最適合的壓縮演算法，從而減小產生之 PDF 文件的大小。 |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | 欲產生之 PDF 文件的符合等級。讀取 [PdfCompliance](../pdfcompliance/)。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 傳回當找不到來源字體時使用的字體。讀取 [System::String](../../system/string/)。 |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | 若為 true，則在每張投影片周圍繪製黑色框線。讀取 **bool**。 |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | 決定是否應嵌入字體的全部字元或僅嵌入使用的子集。讀取 **bool**。 |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | 若為 true，則為 ASCII 字元 32-127 嵌入 TrueType 字體。[Fonts](../../aspose.slides/fonts/) 對於大於 127 的字元代碼則始終嵌入。讀取 **bool**。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 傳回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | 取得影像的透明顏色。 |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | 若為 true，將簡報中的所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 提供控制匯出文件中 [Ink](../../aspose.slides.ink/) 物件外觀的選項。唯讀 [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | 傳回決定 PDF 文件內 JPEG 影像品質的值。讀取 **uint8_t**。 |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | 設定使用者密碼以保護 PDF 文件。讀取 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用於以百分比儲存進度更新的回呼物件。見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | 指示當字體不支援粗體樣式時，文字是否應被光柵化為位圖並儲存至 PDF。此方法可提升某些字體在產生的 PDF 中的文字品質。讀取 **bool**。 |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | 若為 true，將簡報中使用的所有中繪圖檔轉換為 PNG 影像。讀取 **bool**。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定儲存簡報時是否跳過含 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 取得匯出簡報時投影片在頁面上排列的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | 傳回決定 PDF 文件內影像解析度的值。 |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | 指定文件中所有文字內容使用的壓縮類型。讀取 [PdfTextCompression](../pdftextcompression/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 傳回接收警告並決定載入程序是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參照計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型 (targetType) 所描述的實例。相當於 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參照計數。 |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | 包含一組標誌，指定在以使用者身分開啟文件時應授予的存取權限。見 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | 設定字體族群的使用者自訂名稱陣列，[Aspose.Slides](../../aspose.slides/) 應視為通用。寫入 [System::String](../../system/string/)[]。 |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | 如果 **true**，則對影像套用指定的透明顏色。 |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | 指示是否應自動為每張影像選擇最有效的壓縮（而非預設）。若設定為 **bool**.true，則會為簡報中的每張影像挑選最適合的壓縮演算法，從而減小產生之 PDF 文件的大小。 |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | 設定產生的 PDF 文件的符合等級。寫入 [PdfCompliance](../pdfcompliance/)。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 設定當找不到來源字體時使用的字體。寫入 [System::String](../../system/string/)。 |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | 若為 true，則在每張投影片周圍繪製黑色框線。寫入 **bool**。 |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | 決定是否嵌入字體的全部字元或僅嵌入使用的子集。寫入 **bool**。 |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | 若為 true，則為 ASCII 字元 32-127 嵌入 TrueType 字體。[Fonts](../../aspose.slides/fonts/) 對於大於 127 的字元代碼則始終嵌入。寫入 **bool**。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | 設定影像的透明顏色。 |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | 若為 true，將簡報中的所有 OLE 資料轉換為產生的 PDF 中的嵌入檔案。寫入 **bool**。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | 設定決定 PDF 文件內 JPEG 影像品質的值。寫入 **uint8_t**。 |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | 設定使用者密碼以保護 PDF 文件。寫入 [System::String](../../system/string/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用於以百分比儲存進度更新的回呼物件。見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | 指示當字體不支援粗體樣式時，文字是否應被光柵化為位圖並儲存至 PDF。此方法可提升某些字體在產生的 PDF 中的文字品質。寫入 **bool**。 |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | 若為 true，將簡報中使用的所有中繪圖檔轉換為 PNG 影像。寫入 **bool**。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定產生的文件是否應包含隱藏投影片。寫入 **bool**。預設為 **false**。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定儲存簡報時是否跳過含 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 設定匯出簡報時投影片在頁面上排列的模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | 設定決定 PDF 文件內影像解析度的值。 |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | 設定文件中所有文字內容使用的壓縮類型。寫入 [PdfTextCompression](../pdftextcompression/)。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 設定接收警告並決定載入程序是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非 shared）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* 類別 [ISaveOptions](../isaveoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)