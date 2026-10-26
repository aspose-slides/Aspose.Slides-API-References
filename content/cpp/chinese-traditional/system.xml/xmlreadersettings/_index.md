---
title: XmlReaderSettings
second_title: Aspose.Slides for C++ API 參考
description: "指定在由 XmlReader::Create 方法建立的 XmlReader 物件上支援的一組功能。"
type: docs
weight: 443
url: /zh-hant/system.xml/xmlreadersettings/
---
## XmlReaderSettings 類別

指定在 [XmlReader](../xmlreader/) 物件上支援的一組功能，此物件由 [XmlReader::Create](../xmlreader/create/) 方法建立。

```cpp
class XmlReaderSettings : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [CheckReadOnly](./checkreadonly/)(const [String](../../system/string/)\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](./)\> [Clone](./clone/)() | 建立 [XmlReaderSettings](./) 實例的副本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 傳回指示是否執行字元檢查的值。 |
| **bool** [get_CloseInput](./get_closeinput/)() | 傳回指示在關閉讀取器時是否應關閉底層串流或 TextReader 的值。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | 傳回 [XmlReader](../xmlreader/) 所遵循的符合等級。 |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | 傳回決定 DTD 處理方式的值。 |
| **bool** [get_IgnoreComments](./get_ignorecomments/)() | 傳回指示是否忽略註解的值。 |
| **bool** [get_IgnoreProcessingInstructions](./get_ignoreprocessinginstructions/)() | 傳回指示是否忽略處理指令的值。 |
| **bool** [get_IgnoreWhitespace](./get_ignorewhitespace/)() | 傳回指示是否忽略無意義空白字元的值。 |
| **int32_t** [get_LineNumberOffset](./get_linenumberoffset/)() | 傳回 [XmlReader](../xmlreader/) 物件的行號偏移。 |
| **int32_t** [get_LinePositionOffset](./get_linepositionoffset/)() | 傳回 [XmlReader](../xmlreader/) 物件的行位置偏移。 |
| **int64_t** [get_MaxCharactersFromEntities](./get_maxcharactersfromentities/)() | 傳回指示因展開實體而產生的文件最大允許字元數的值。 |
| **int64_t** [get_MaxCharactersInDocument](./get_maxcharactersindocument/)() | 傳回指示 XML 文件最大允許字元數的值。零 (0) 表示對 XML 文件大小沒有限制。非零值指定以字元為單位的最大大小。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 傳回用於原子化字串比較的 [XmlNameTable](../xmlnametable/)。 |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 傳回指示是否禁止文件類型定義 (DTD) 處理的值。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | 傳回執行綱要驗證時使用的 XmlSchemaSet。 |
| [Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/) [get_ValidationFlags](./get_validationflags/)() | 傳回指示綱要驗證設定的值。此設定套用於驗證綱要的 [XmlReader](../xmlreader/) 物件 ([XmlReaderSettings::get_ValidationType](./get_validationtype/) 值為 [ValidationType::Schema](../validationtype/))。 |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 傳回指示在讀取時 [XmlReader](../xmlreader/) 是否執行驗證或類型指派的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 針對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 針對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [Reset](./reset/)() | 將設定類別的成員重設為預設值。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 設定指示是否執行字元檢查的值。 |
| void [set_CloseInput](./set_closeinput/)(**bool**) | 設定在關閉讀取器時是否應關閉底層串流或 TextReader 的值。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | 設定 [XmlReader](../xmlreader/) 所遵循的符合等級。 |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | 設定決定 DTD 處理方式的值。 |
| void [set_IgnoreComments](./set_ignorecomments/)(**bool**) | 設定指示是否忽略註解的值。 |
| void [set_IgnoreProcessingInstructions](./set_ignoreprocessinginstructions/)(**bool**) | 設定指示是否忽略處理指令的值。 |
| void [set_IgnoreWhitespace](./set_ignorewhitespace/)(**bool**) | 設定指示是否忽略無意義空白字元的值。 |
| void [set_LineNumberOffset](./set_linenumberoffset/)(**int32_t**) | 設定 [XmlReader](../xmlreader/) 物件的行號偏移。 |
| void [set_LinePositionOffset](./set_linepositionoffset/)(**int32_t**) | 設定 [XmlReader](../xmlreader/) 物件的行位置偏移。 |
| void [set_MaxCharactersFromEntities](./set_maxcharactersfromentities/)(**int64_t**) | 設定因展開實體而產生的文件最大允許字元數的值。 |
| void [set_MaxCharactersInDocument](./set_maxcharactersindocument/)(**int64_t**) | 設定 XML 文件最大允許字元數的值。零 (0) 表示對文件大小沒有限制。非零值指定以字元為單位的最大大小。 |
| void [set_NameTable](./set_nametable/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 設定用於原子化字串比較的 [XmlNameTable](../xmlnametable/)。 |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | 設定指示是否禁止文件類型定義 (DTD) 處理的值。 |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | 設定執行綱要驗證時使用的 XmlSchemaSet。 |
| void [set_ValidationFlags](./set_validationflags/)([Schema::XmlSchemaValidationFlags](../../system.xml.schema/xmlschemavalidationflags/)) | 設定指示綱要驗證設定的值。此設定套用於驗證綱要的 [XmlReader](../xmlreader/) 物件 ([XmlReaderSettings::get_ValidationType](./get_validationtype/) 值為 [ValidationType::Schema](../validationtype/))。 |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 設定指示在讀取時 [XmlReader](../xmlreader/) 是否執行驗證或類型指派的值。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 設定用於存取外部文件的 [XmlResolver](../xmlresolver/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解除鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視器物件。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args…) | 加入讀取器遇到驗證錯誤時觸發的事件處理程式。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args…) | 移除讀取器遇到驗證錯誤時觸發的事件處理程式。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlReaderSettings](./xmlreadersettings/)() | 初始化 [XmlReaderSettings](./) 類別的新實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 類型別名

| 類型別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別之實例的共享指標別名。 |

## 備註

此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)