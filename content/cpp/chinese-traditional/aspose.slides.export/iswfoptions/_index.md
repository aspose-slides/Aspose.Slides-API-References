---
title: ISwfOptions
second_title: Aspose.Slides for C++ API 參考
description: 提供控制簡報以 SWF 格式儲存的選項。
type: docs
weight: 469
url: /zh-hant/aspose.slides.export/iswfoptions/
---
## ISwfOptions 類別

Provides options that control how a presentation is saved in SWF format.

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **bool** [get_Compressed](./get_compressed/)() | 指定產生的 SWF 文件是否應壓縮。預設為 **true**。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 在未找到來源字型時回傳使用的字型。讀取 [System::String](../../system/string/)。 |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | 啟用/停用右鍵功能表。預設為 true。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | 回傳漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | 指定 JPEG 圖片的品質。  

 預設為 95。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | 將於檢視器右上角顯示為標誌的圖像。  

 圖像應為 32x64 像素的 PNG 圖檔，否則標誌可能無法正確顯示。 |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | 取得標誌的完整超連結位址。僅在指定 [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) 時才會生效。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 代表以百分比表示的儲存進度更新之回呼物件。另見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | 顯示/隱藏底部面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | 顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | 顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | 指定是否顯示頁面周圍的邊框。預設為 true。 |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | 顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | 顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | 顯示/隱藏整個頂部面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | 取得匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時，投影片在頁面上放置的模式。此屬性不支援指派 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 類型的物件。 |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | 預設以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。 |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | 指定產生的 SWF 文件是否應包含內嵌文件檢視器。預設為 **true**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 回傳接收警告並決定載入程序是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | 指定產生的 SWF 文件是否應壓縮。預設為 **true**。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 設定在未找到來源字型時使用的字型。寫入 [System::String](../../system/string/)。 |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | 啟用/停用右鍵功能表。預設為 true。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | 指定 JPEG 圖片的品質。  

 預設為 95。 |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | 將於檢視器右上角顯示為標誌的圖像。  

 圖像應為 32x64 像素的 PNG 圖檔，否則標誌可能無法正確顯示。 |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | 設定標誌的完整超連結位址。僅在指定 [set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) 時才會生效。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 代表以百分比表示的儲存進度更新之回呼物件。另見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | 顯示/隱藏底部面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | 顯示/隱藏全螢幕按鈕。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | 顯示/隱藏左側面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | 指定是否顯示頁面周圍的邊框。預設為 true。 |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | 顯示/隱藏頁面步進器。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | 顯示/隱藏搜尋區段。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | 顯示/隱藏整個頂部面板。可在 flashvars 中覆寫。預設為 true。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | 指定在儲存簡報時是否跳過帶有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | 設定匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時，投影片在頁面上放置的模式。此屬性不支援指派 **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 類型的物件。 |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | 預設以開啟的左側面板開始。可在 flashvars 中覆寫。預設為 false。 |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | 指定產生的 SWF 文件是否應包含內嵌文件檢視器。預設為 **true**。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 設定接收警告並決定載入程序是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 另見

* 類別 [ISaveOptions](../isaveoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)