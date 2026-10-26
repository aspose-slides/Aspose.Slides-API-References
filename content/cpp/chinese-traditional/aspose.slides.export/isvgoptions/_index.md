---
title: ISVGOptions
second_title: Aspose.Slides for C++ API 參考
description: 表示 SVG 選項。
type: docs
weight: 404
url: /zh-hant/aspose.slides.export/isvgoptions/
---
## ISVGOptions 類別


表示 SVG 選項。

```cpp
class ISVGOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 返回在未找到來源字型時使用的字型。讀取 [System::String](../../system/string/)。 |
| virtual **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() | 布林旗標指示裁剪的部份是否仍保留在文件中。若為 true，裁剪的部份將被移除；若為 false，則會在文件中序列化（可能導致檔案變大）。讀取 **bool**。 |
| virtual **bool** [get_Disable3DText](./get_disable3dtext/)() | 判斷 SVG 中的 3D 文字是否已停用。讀取 **bool**。 |
| virtual **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() | 取得表示文字是否在未使用連字情況下渲染的值。設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設為 **false**。 |
| virtual **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() | 停用 FromCornerX 與 FromCenter 漸層的分割。讀取 **bool**。 |
| virtual **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() | SVG 1.1 缺乏為標記定義內縮的能力。[Aspose.Slides](../../aspose.slides/) SVG 寫入引擎對此問題有解決方法：它會裁剪帶箭頭的線段末端，使線條不會與標記重疊。此選項可關閉該行為。讀取 **bool**。 |
| virtual [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() | 決定處理外部載入字型的方式。讀取 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 返回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | 提供控制匯出文件中 [Ink](../../aspose.slides.ink/) 物件外觀的選項。唯讀 [IInkOptions](../iinkoptions/) |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | 決定 JPEG 編碼品質。讀取 **int32_t**。 |
| virtual **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() | 返回位圖檔案光柵化的最低解析度限制。讀取 **int32_t**。 |
| virtual [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() | 表示圖片壓縮等級。讀取 [PicturesCompression](../picturescompression/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 表示用於以百分比保存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() | 返回並設定允許使用者控制形狀轉換的回呼介面。讀取 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在保存簡報時是否跳過帶有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| virtual **bool** [get_UseFrameRotation](./get_useframerotation/)() | 判斷在渲染時是否執行指定的形狀旋轉。讀取 **bool**。預設值為 true。 |
| virtual **bool** [get_UseFrameSize](./get_useframesize/)() | 判斷文字框是否會被包含在渲染區域中。讀取 **bool**。預設值為 false。 |
| virtual **bool** [get_VectorizeText](./get_vectorizetext/)() | 判斷投影片上的文字是否會以圖形形式保存。讀取 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 返回一個接收警告並決定載入過程是繼續還是中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的型別實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 設定在未找到來源字型時使用的字型。寫入 [System::String](../../system/string/)。 |
| virtual void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) | 布林旗標指示裁剪的部份是否仍保留在文件中。若為 true，裁剪的部份將被移除；若為 false，則會在文件中序列化（可能導致檔案變大）。寫入 **bool**。 |
| virtual void [set_Disable3DText](./set_disable3dtext/)(**bool**) | 判斷 SVG 中的 3D 文字是否已停用。寫入 **bool**。 |
| virtual void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) | 設定表示文字是否在未使用連字情況下渲染的值。設定為 **true** 時，連字將在渲染輸出中被停用。預設情況下，此屬性設為 **false**。 |
| virtual void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) | 停用 FromCornerX 與 FromCenter 漸層的分割。寫入 **bool**。 |
| virtual void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) | SVG 1.1 缺乏為標記定義內縮的能力。[Aspose.Slides](../../aspose.slides/) SVG 寫入引擎對此問題有解決方法：它會裁剪帶箭頭的線段末端，使線條不會與標記重疊。此選項可關閉該行為。寫入 **bool**。 |
| virtual void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) | 決定處理外部載入字型的方式。寫入 [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | 決定 JPEG 編碼品質。寫入 **int32_t**。 |
| virtual void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) | 設定位圖檔案光柵化的最低解析度限制。寫入 **int32_t**。 |
| virtual void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) | 表示圖片壓縮等級。寫入 [PicturesCompression](../picturescompression/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 表示用於以百分比保存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) | 返回並設定允許使用者控制形狀轉換的回呼介面。寫入 [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在保存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| virtual void [set_UseFrameRotation](./set_useframerotation/)(**bool**) | 判斷在渲染時是否執行指定的形狀旋轉。寫入 **bool**。預設值為 true。 |
| virtual void [set_UseFrameSize](./set_useframesize/)(**bool**) | 判斷文字框是否會被包含在渲染區域中。寫入 **bool**。預設值為 false。 |
| virtual void [set_VectorizeText](./set_vectorizetext/)(**bool**) | 判斷投影片上的文字是否會以圖形形式保存。寫入 **bool**。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 設定接收警告並決定載入過程是繼續還是中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [ISaveOptions](../isaveoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)