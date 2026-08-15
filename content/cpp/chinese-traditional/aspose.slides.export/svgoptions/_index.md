---
title: SVGOptions
second_title: Aspose.Slides C++ 版 API 參考
description: 表示 SVG 選項。
type: docs
weight: 703
url: /zh-hant/aspose.slides.export/svgoptions/
---
## SVGOptions 類別

表示 SVG 選項。

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | 傳回預設設定。唯讀 [SVGOptions](./)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 在找不到來源字型時傳回使用的字型。讀取 [System::String](../../system/string/)。 |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | 布林旗標，指示裁切部份是否保留在文件中。若為 true，裁切部份將被移除；若為 false，則會序列化至文件（可能導致檔案變大）。 |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | 判斷 SVG 中是否停用 3D 文字。讀取 **bool**。 |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | 取得指示文字是否在不使用連字的情況下呈現的值。設定為 **true** 時，連字將在輸出中被停用。預設為 **false**。 |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | 停用 FromCornerX 與 FromCenter 漸層的分割。讀取 **bool**。 |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 無法為標記定義內縮。[Aspose.Slides](../../aspose.slides/) SVG 寫入引擎針對此問題提供變通：裁剪含箭頭的線段末端，使線段不會與標記重疊。此選項可關閉此行為。讀取 **bool**。 |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | 判斷外部載入字型的處理方式。讀取 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 傳回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | 提供控制匯出文件中 [Ink](../../aspose.slides.ink/) 物件外觀的選項。唯讀 [IInkOptions](../iinkoptions/)。 |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | 判斷 JPEG 編碼品質。讀取 **int32_t**。 |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | 傳回影像檔光柵化的最低解析度限制。讀取 **int32_t**。 |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | 表示圖片壓縮等級。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示以百分比儲存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | 傳回並設定允許使用者控制形狀轉換的回呼介面。讀取 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | 傳回最簡單且最小的 SVG 檔案產生設定。唯讀 [SVGOptions](./)。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | 判斷在渲染時是否執行指定的形狀旋轉。讀取 **bool**。預設值為 true。 |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | 判斷文字框是否會包含在渲染區域中。讀取 **bool**。預設值為 false。 |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | 判斷投影片上的文字是否會儲存為圖形。讀取 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 傳回或設定接收警告且決定載入過程是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | 傳回最精確 SVG 檔案產生設定。唯讀 [SVGOptions](./)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類比。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。C# `is` 運算子的類比。 |
| void [Lock](../../system/object/lock/)() | 實作 C# `lock()` 陳述式的鎖定功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) sentinel 物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 為字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 為字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值降低共享參考計數。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 設定在找不到來源字型時使用的字型。寫入 [System::String](../../system/string/)。 |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | 布林旗標，指示裁切部份是否保留在文件中。若為 true，裁切部份將被移除；若為 false，則會序列化至文件（可能導致檔案變大）。 |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | 判斷 SVG 中是否停用 3D 文字。寫入 **bool**。 |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | 設定文字是否在不使用連字的情況下呈現。設定為 **true** 時，連字將在輸出中被停用。預設為 **false**。 |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | 停用 FromCornerX 與 FromCenter 漸層的分割。寫入 **bool**。 |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 無法為標記定義內縮。[Aspose.Slides](../../aspose.slides/) SVG 寫入引擎針對此問題提供變通：裁剪含箭頭的線段末端，使線段不會與標記重疊。此選項可關閉此行為。寫入 **bool**。 |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | 判斷外部載入字型的處理方式。寫入 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | 判斷 JPEG 編碼品質。寫入 **int32_t**。 |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | 設定影像檔光柵化的最低解析度限制。寫入 **int32_t**。 |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | 表示圖片壓縮等級。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示以百分比儲存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | 傳回並設定允許使用者控制形狀轉換的回呼介面。寫入 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在儲存簡報時是否跳過包含 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | 判斷在渲染時是否執行指定的形狀旋轉。寫入 **bool**。預設值為 true。 |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | 判斷文字框是否會包含在渲染區域中。寫入 **bool**。預設值為 false。 |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | 判斷投影片上的文字是否會儲存為圖形。寫入 **bool**。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 傳回或設定接收警告且決定載入過程是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少共享參考計數並傳回其新值。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
|  [SVGOptions](./svgoptions/)() | 初始化 [SVGOptions](./) 類別的新實例。 |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | 初始化 [SVGOptions](./) 類別的新實例，並指定連結嵌入控制器物件。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# `typeof([System.Object](../../system/object/))` 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# `lock()` 陳述式的解鎖功能。直接呼叫或使用 [LockContext](../../system/lockcontext/) sentinel 物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另請參閱

* Class [SaveOptions](../saveoptions/)
* Class [ISVGOptions](../isvgoptions/)
* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)