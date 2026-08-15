---
title: MarkdownSaveOptions
second_title: Aspose.Slides for C++ API 參考
description: 表示控制簡報如何儲存為 markdown 的選項。
type: docs
weight: 547
url: /zh-hant/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions 類別


表示控制簡報如何儲存為 markdown 的選項。

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）都不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | 指定含資源的文件將被儲存的基礎路徑。預設為應用程式的目前目錄。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | 在找不到來源字型時返回使用的字型。讀取 [System::String](../../system/string/)。 |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | 指定將簡報轉換為 markdown 的規格。預設為 **TextOnly**。 |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | 指定將簡報轉換為 markdown 的規格。預設為 **Multi-markdown**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | 返回漸層的視覺樣式。讀取 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | 指定在 Markdown 匯出時如何處理重複的普通空格字元。 |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | 指定儲存影像的資料夾名稱。預設為 **[Images](../../aspose.slides/images/)**。 |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | 指定產生的文件應使用的換行符為 \r（Macintosh）、\n（Unix）或 \r\n（Windows）。預設為 **Unix**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 代表以百分比形式提供儲存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | 若設為 **true**，將從最終的 Markdown 輸出中移除空行或僅包含空白的行。預設為 **false**。 |
| **bool** [get_ShowComments](./get_showcomments/)() const | 指定產生的文件是否顯示註解。預設為 **false**。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | 指定產生的文件是否包含隱藏投影片。預設為 **false**。 |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | 指定產生的文件是否顯示每張投影片的編號。預設為 **false**。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | 指定在儲存簡報時是否跳過含 JavaScript 呼叫的超連結。讀取 **bool**。預設值為 **false**。 |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | 取得在 Markdown 輸出中用於投影片編號標題的格式字串。格式必須包含 \"{0}\" 佔位符，於匯出時會被投影片索引取代。例如：\"# Slide {0}\" 會產生 \"# Slide 1\", \"# Slide 2\", 等。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。讀取 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | 建構子。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特殊化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特殊化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | 指定含資源的文件將被儲存的基礎路徑。預設為應用程式的目前目錄。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 在找不到來源字型時設定使用的字型。寫入 [System::String](../../system/string/)。 |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | 指定將簡報轉換為 markdown 的規格。預設為 **TextOnly**。 |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | 指定將簡報轉換為 markdown 的規格。預設為 **Multi-markdown**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | 設定漸層的視覺樣式。寫入 [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | 指定在 Markdown 匯出時如何處理重複的普通空格字元。 |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | 指定儲存影像的資料夾名稱。預設為 **[Images](../../aspose.slides/images/)**。 |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | 指定產生的文件應使用的換行符為 \r（Macintosh）、\n（Unix）或 \r\n（Windows）。預設為 **Unix**。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 代表以百分比形式提供儲存進度更新的回呼物件。請參閱 [IProgressCallback](../../aspose.slides/iprogresscallback/)。 |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | 若設為 **true**，將從最終的 Markdown 輸出中移除空行或僅包含空白的行。預設為 **false**。 |
| void [set_ShowComments](./set_showcomments/)(**bool**) | 指定產生的文件是否顯示註解。預設為 **false**。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 指定產生的文件是否包含隱藏投影片。預設為 **false**。 |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | 指定產生的文件是否顯示每張投影片的編號。預設為 **false**。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | 指定在儲存簡報時是否跳過含 JavaScript 呼叫的超連結。寫入 **bool**。預設值為 **false**。 |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | 取得在 Markdown 輸出中用於投影片編號標題的格式字串。格式必須包含 \"{0}\" 佔位符，於匯出時會被投影片索引取代。例如：\"# Slide {0}\" 會產生 \"# Slide 1\", \"# Slide 2\", 等。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 返回或設定一個接收警告並決定載入過程是否繼續或中止的物件。寫入 [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | 在 Markdown 匯出期間，對每個非 SVG 圖像（點陣圖或圖樣）呼叫。 
 返回 **true** 以使用指定的 *link* , 
 或 **false** 以套用預設的儲存邏輯。 |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | 在 Markdown 匯出期間，對每個 SVG 圖像呼叫。 
 返回 **true** 以使用指定的 *link* , 
 或 **false** 以套用預設的儲存邏輯。 |

## 備註

範例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## 另見

* 類別 [SaveOptions](../saveoptions/)
* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)