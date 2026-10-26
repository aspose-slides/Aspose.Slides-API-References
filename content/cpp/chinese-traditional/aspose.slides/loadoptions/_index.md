---
title: LoadOptions
second_title: Aspose.Slides for C++ API 參考文件
description: 允許在載入簡報時指定額外選項（例如格式或預設字型）。
type: docs
weight: 4395
url: /zh-hant/aspose.slides/loadoptions/
---
## LoadOptions 類別


允許在載入簡報時指定額外選項（例如格式或預設字型）。

```cpp
class LoadOptions : public Aspose::Slides::ILoadOptions
```

## 方法

| Method | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\> [get_BlobManagementOptions](./get_blobmanagementoptions/)() override | 表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用臨時檔案或記憶體中 BLOB 的最大位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體消耗比例。 |
| [System::String](../../system/string/) [get_DefaultAsianFont](./get_defaultasianfont/)() override | 返回在找不到來源字型時使用的亞洲字型。閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](./get_defaultregularfont/)() override | 返回在找不到來源字型時使用的常規字型。閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultSymbolFont](./get_defaultsymbolfont/)() override | 返回在找不到來源字型時使用的符號字型。閱讀 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_DefaultTextLanguage](./get_defaulttextlanguage/)() override | 返回簡報文字的預設語言。閱讀 [System::String](../../system/string/)。 |
| **bool** [get_DeleteEmbeddedBinaryObjects](./get_deleteembeddedbinaryobjects/)() override | 判斷在載入簡報時 [Aspose.Slides](../) 是否會刪除所有嵌入的二進位物件。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\> [get_DocumentLevelFontSources](./get_documentlevelfontsources/)() override | 指定簡報使用的外部字型來源。這些字型在簡報的整個壽命期間皆可使用，且不會與其他簡報共享。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\> [get_InterruptionToken](./get_interruptiontoken/)() override | 用於監控中斷請求的代幣。 |
| [Aspose::Slides::LoadFormat](../loadformat/) [get_LoadFormat](./get_loadformat/)() override | 返回要載入的簡報格式。閱讀 [Slides::LoadFormat](../loadformat/)。 |
| **bool** [get_OnlyLoadDocumentProperties](./get_onlyloaddocumentproperties/)() override | 此屬性在簡報檔案受密碼保護時才有意義。值為 true 表示僅需從加密的簡報檔案載入文件屬性，且忽略密碼。值為 false 表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則此屬性值始終被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，將拋出例外。閱讀 **bool**。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | 取得密碼。閱讀 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\> [get_ResourceLoadingCallback](./get_resourceloadingcallback/)() override | 返回管理外部資源載入的回呼介面。閱讀 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\> [get_SpreadsheetOptions](./get_spreadsheetoptions/)() override | 取得試算表的選項。例如，這些選項會影響圖表公式的計算。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](./get_warningcallback/)() override | 返回一個接收警告並決定載入過程是否繼續或中止的物件。閱讀 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 'is' 運算子。 |
|  [LoadOptions](./loadoptions/)() | 建立新的預設載入選項。 |
|  [LoadOptions](./loadoptions/)([Aspose::Slides::LoadFormat](../loadformat/)) | 建立新的載入選項。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上並不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上並不複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_BlobManagementOptions](./set_blobmanagementoptions/)([System::SharedPtr](../../system/sharedptr/)\<[IBlobManagementOptions](../iblobmanagementoptions/)\>) override | 表示可用於管理大型二進位物件 (BLOB) 處理行為的選項，例如使用臨時檔案或記憶體中 BLOB 的最大位元組數。這些選項旨在為特定環境或需求設定最佳的效能/記憶體消耗比例。 |
| void [set_DefaultAsianFont](./set_defaultasianfont/)([System::String](../../system/string/)) override | 設定在找不到來源字型時使用的亞洲字型。寫入 [System::String](../../system/string/)。 |
| void [set_DefaultRegularFont](./set_defaultregularfont/)([System::String](../../system/string/)) override | 設定在找不到來源字型時使用的常規字型。寫入 [System::String](../../system/string/)。 |
| void [set_DefaultSymbolFont](./set_defaultsymbolfont/)([System::String](../../system/string/)) override | 設定在找不到來源字型時使用的符號字型。寫入 [System::String](../../system/string/)。 |
| void [set_DefaultTextLanguage](./set_defaulttextlanguage/)([System::String](../../system/string/)) override | 設定簡報文字的預設語言。寫入 [System::String](../../system/string/)。 |
| void [set_DeleteEmbeddedBinaryObjects](./set_deleteembeddedbinaryobjects/)(**bool**) override | 判斷在載入簡報時 [Aspose.Slides](../) 是否會刪除所有嵌入的二進位物件。 |
| void [set_DocumentLevelFontSources](./set_documentlevelfontsources/)([System::SharedPtr](../../system/sharedptr/)\<[IFontSources](../ifontsources/)\>) override | 指定簡報使用的外部字型來源。這些字型在簡報的整個壽命期間皆可使用，且不會與其他簡報共享。 |
| void [set_InterruptionToken](./set_interruptiontoken/)([System::SharedPtr](../../system/sharedptr/)\<[IInterruptionToken](../iinterruptiontoken/)\>) override | 用於監控中斷請求的代幣。 |
| void [set_LoadFormat](./set_loadformat/)([Aspose::Slides::LoadFormat](../loadformat/)) override | 設定要載入的簡報格式。寫入 [Slides::LoadFormat](../loadformat/)。 |
| void [set_OnlyLoadDocumentProperties](./set_onlyloaddocumentproperties/)(**bool**) override | 此屬性在簡報檔案受密碼保護時才有意義。值為 true 表示僅需從加密的簡報檔案載入文件屬性，且忽略密碼。值為 false 表示必須使用正確的密碼載入整個加密的簡報。若簡報未加密，則此屬性值始終被忽略。若加密檔案的文件屬性不是公開的且屬性值為 true，則無法載入文件屬性，將拋出例外。寫入 **bool**。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | 設定密碼。寫入 [System::String](../../system/string/)。 |
| void [set_ResourceLoadingCallback](./set_resourceloadingcallback/)([System::SharedPtr](../../system/sharedptr/)\<[IResourceLoadingCallback](../iresourceloadingcallback/)\>) override | 設定管理外部資源載入的回呼介面。寫入 [IResourceLoadingCallback](../iresourceloadingcallback/)。 |
| void [set_SpreadsheetOptions](./set_spreadsheetoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISpreadsheetOptions](../ispreadsheetoptions/)\>) override | 取得試算表的選項。例如，這些選項會影響圖表公式的計算。 |
| void [set_WarningCallback](./set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 設定一個接收警告並決定載入過程是否繼續或中止的物件。寫入 [Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
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

* 類別 [ILoadOptions](../iloadoptions/)
* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)