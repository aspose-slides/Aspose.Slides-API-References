---
title: SwfOptions
second_title: Aspose.Slides for C++ API 參考
description: 提供控制簡報以 Swf 格式儲存方式的選項。
type: docs
weight: 742
url: /zh-hant/aspose.slides.export/swfoptions/
---
## SwfOptions 類別

提供控制簡報以 Swf 格式儲存方式的選項。

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_Compressed](./get_compressed/)() override | 指定產生的 SWF 文件是否應壓縮。預設為 **true**。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 在找不到來源字型時返回使用的字型。讀取 [System::String](../../system/string/)。 |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | 啟用/停用右鍵功能表。預設為 true。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | 指定 JPEG 圖片的品質。預設為 95。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | 在檢視器右上角顯示的圖片作為標誌。圖片應為 32x64 像素的 PNG 圖片，否則標誌可能顯示不正確。 |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | 取得標誌的完整超連結位址。僅在指定了 [set_LogoImageBytes()](./set_logoimagebytes/) 時才有效。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 表示用於以百分比儲存進度更新的回呼物件。參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | 顯示/隱藏底部面板。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | 顯示/隱藏全螢幕按鈕。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | 顯示/隱藏左側面板。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | 指定是否顯示頁面周圍的邊框。預設為 true。 |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | 顯示/隱藏頁面步進器。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_ShowSearch](./get_showsearch/)() override | 顯示/隱藏搜尋區段。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | 顯示/隱藏整個頂部面板。可於 flashvars 中覆寫。預設為 true。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | 取得匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時投影片在頁面上的排列模式。此屬性不支援指派 [HandoutLayoutingOptions](../handoutlayoutingoptions/) 類型的物件。 |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | 以開啟的左側面板開始。可於 flashvars 中覆寫。預設為 false。 |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | 指定產生的 SWF 文件是否應包含整合的文件檢視器。預設為 **true**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或設定接收警告並決定載入過程是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的引用計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以引用方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以引用方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享引用計數減少指定的值。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | 指定產生的 SWF 文件是否應壓縮。預設為 **true**。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 在找不到來源字型時設定使用的字型。寫入 [System::String](../../system/string/)。 |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | 啟用/停用右鍵功能表。預設為 true。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | 指定 JPEG 圖片的品質。預設為 95。 |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | 在檢視器右上角顯示的圖片作為標誌。圖片應為 32x64 像素的 PNG 圖片，否則標誌可能顯示不正確。 |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | 設定標誌的完整超連結位址。僅在指定了 [set_LogoImageBytes()](./set_logoimagebytes/) 時才有效。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 表示用於以百分比儲存進度更新的回呼物件。參見 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | 顯示/隱藏底部面板。可於 flashvars 中覆寫。預設為 true。 |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | 顯示/隱藏全螢幕按鈕。可於 flashvars 中覆寫。預設為 true。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 指定產生的文件是否應包含隱藏投影片。預設為 **false**。 |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | 顯示/隱藏左側面板。可於 flashvars 中覆寫。預設為 true。 |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | 指定是否顯示頁面周圍的邊框。預設為 true。 |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | 顯示/隱藏頁面步進器。可於 flashvars 中覆寫。預設為 true。 |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | 顯示/隱藏搜尋區段。可於 flashvars 中覆寫。預設為 true。 |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | 顯示/隱藏整個頂部面板。可於 flashvars 中覆寫。預設為 true。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在儲存簡報時是否跳過含有 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | 設定匯出簡報 [ISlidesLayoutOptions](../islideslayoutoptions/) 時投影片在頁面上的排列模式。此屬性不支援指派 [HandoutLayoutingOptions](../handoutlayoutingoptions/) 類型的物件。 |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | 以開啟的左側面板開始。可於 flashvars 中覆寫。預設為 false。 |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | 指定產生的 SWF 文件是否應包含整合的文件檢視器。預設為 **true**。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或設定接收警告並決定載入過程是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享引用計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [SwfOptions](./swfoptions/)() | 預設建構子。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 守護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱引用計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 備註

以下範例說明如何將 PowerPoint 轉換為 SWF Flash。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## 另請參閱

* 類別 [SaveOptions](../saveoptions/)
* 類別 [ISwfOptions](../iswfoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)