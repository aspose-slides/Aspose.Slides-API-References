---
title: TiffOptions
second_title: Aspose.Slides for C++ API 參考文件
description: 提供控制簡報以 TIFF 格式儲存的選項。
type: docs
weight: 768
url: /zh-hant/aspose.slides.export/tiffoptions/
---
## TiffOptions 類別


提供控制簡報以 TIFF 格式儲存方式的選項。

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | 指定將彩色影像轉換為黑白影像的演算法。此選項僅在 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) 設為 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 時套用。讀取 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。預設為 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | 指定壓縮類型。讀取 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 返回在找不到來源字型時使用的字型。讀取 [System::String](../../system/string/)。 |
| **uint32_t** [get_DpiX](./get_dpix/)() override | 指定水平解析度（每英寸點數）。讀取 **uint32_t**。 |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | 指定垂直解析度（每英寸點數）。讀取 **uint32_t**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | 指定產生之 TIFF 圖像的大小。預設值為 0x0，表示將根據簡報投影片大小計算圖像尺寸。讀取 [System::Drawing::Size](../../system.drawing/size/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制匯出文件中 [Ink](../../aspose.slides.ink/) 物件外觀的選項。唯讀 [IInkOptions](../iinkoptions/)。 |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | 指定產生圖像的像素格式。讀取 [ImagePixelFormat](../imagepixelformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 代表以百分比表示儲存進度更新的回呼物件。參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 取得匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或設定接收警告並決定載入程序是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | 指定將彩色影像轉換為黑白影像的演算法。此選項僅在 [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) 設為 [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) 時套用。寫入 [BlackWhiteConversionMode](../blackwhiteconversionmode/)。預設為 [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)。 |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | 指定壓縮類型。寫入 [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 設定在找不到來源字型時使用的字型。寫入 [System::String](../../system/string/)。 |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | 指定水平解析度（每英寸點數）。寫入 **uint32_t**。 |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | 指定垂直解析度（每英寸點數）。寫入 **uint32_t**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | 指定產生之 TIFF 圖像的大小。預設值為 0x0，表示將根據簡報投影片大小計算圖像尺寸。寫入 [System::Drawing::Size](../../system.drawing/size/)。 |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | 指定產生圖像的像素格式。寫入 [ImagePixelFormat](../imagepixelformat/)。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 代表以百分比表示儲存進度更新的回呼物件。參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 設定匯出簡報時投影片在頁面上的排列模式 [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或設定接收警告並決定載入程序是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [TiffOptions](./tiffoptions/)() | 預設建構函式。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註


以下範例示範如何以預設大小將 PowerPoint 轉換為 TIFF。  
```cpp
// 建立一個代表簡報檔案的 Presentation 物件
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// 將簡報儲存為 TIFF 文件
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
以下範例示範如何以自訂大小將 PowerPoint 轉換為 TIFF。  
```cpp
// 建立一個代表簡報檔案的 Presentation 物件
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// 建立 TiffOptions 類別的實例
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// 設定壓縮類型
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// 壓縮類型
// Default - 指定預設的壓縮方案 (LZW).
// None - 指定不使用壓縮.
// CCITT3
// CCITT4
// LZW
// RLE
// 深度取決於壓縮類型，無法手動設定.
// 解析度單位始終等於 "2"（每英寸點數）
 // 設定影像 DPI
opts->set_DpiX(200);
opts->set_DpiY(100);
// 設定影像大小
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// 以指定的影像大小將簡報儲存為 TIFF
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
以下範例示範如何以自訂影像像素格式將 PowerPoint 轉換為 TIFF。  
```cpp
// 建立一個代表簡報檔案的 Presentation 物件
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// 以指定的影像大小將簡報儲存為 TIFF
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## 參見

* 類別 [SaveOptions](../saveoptions/)
* 類別 [ITiffOptions](../itiffoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)