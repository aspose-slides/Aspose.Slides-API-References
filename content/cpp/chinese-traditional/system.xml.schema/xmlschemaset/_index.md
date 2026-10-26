---
title: XmlSchemaSet
second_title: Aspose.Slides for C++ API 參考文件
description: 包含 XML Schema 定義語言 (XSD) 架構的快取。
type: docs
weight: 781
url: /zh-hant/system.xml.schema/xmlschemaset/
---
## XmlSchemaSet 類別

包含 XML [Schema](../) 定義語言 (XSD) 架構的快取。

```cpp
class XmlSchemaSet : public System::Object
```

## 方法

| 方法 | 說明 |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [String](../../system/string/)\&) | 將在指定 URL 的 XML [Schema](../) 定義語言 (XSD) 架構加入至 [XmlSchemaSet](./)。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)([String](../../system/string/), const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | 將包含於 [XmlReader](../../system.xml/xmlreader/) 的 XML [Schema](../) 定義語言 (XSD) 架構加入至 [XmlSchemaSet](./)。 |
| void [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSet](./)\>\&) | 將給定 [XmlSchemaSet](./) 中的所有 XML [Schema](../) 定義語言 (XSD) 架構加入至 [XmlSchemaSet](./)。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Add](./add/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 將給定的 [XmlSchema](../xmlschema/) 加入至 [XmlSchemaSet](./)。 |
| void [Compile](./compile/)() | 將加入至 [XmlSchemaSet](./) 的 XML [Schema](../) 定義語言 (XSD) 架構編譯為一個邏輯架構。 |
| **bool** [Contains](./contains/)([String](../../system/string/)) | 指示具有指定目標命名空間 URI 的 XML [Schema](../) 定義語言 (XSD) 架構是否位於 [XmlSchemaSet](./) 中。 |
| **bool** [Contains](./contains/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 指示指定的 XML [Schema](../) 定義語言 (XSD) [XmlSchema](../xmlschema/) 物件是否位於 [XmlSchemaSet](./) 中。 |
| void [CopyTo](./copyto/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\&, **int32_t**) | 將所有 [XmlSchema](../xmlschema/) 物件從 [XmlSchemaSet](./) 複製到給定的陣列，從指定的索引開始。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\> [get_CompilationSettings](./get_compilationsettings/)() | 傳回 [XmlSchemaSet](./) 的 [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)。 |
| **int32_t** [get_Count](./get_count/)() | 傳回 [XmlSchemaSet](./) 中邏輯 XML [Schema](../) 定義語言 (XSD) 架構的數量。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalAttributes](./get_globalattributes/)() | 傳回 [XmlSchemaSet](./) 中所有 XML [Schema](../) 定義語言 (XSD) 架構的全域屬性。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalElements](./get_globalelements/)() | 傳回 [XmlSchemaSet](./) 中所有 XML [Schema](../) 定義語言 (XSD) 架構的全域元素。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_GlobalTypes](./get_globaltypes/)() | 傳回 [XmlSchemaSet](./) 中所有 XML [Schema](../) 定義語言 (XSD) 架構的全域簡單與複雜類型。 |
| **bool** [get_IsCompiled](./get_iscompiled/)() | 傳回一個值，指示 [XmlSchemaSet](./) 中的 XML [Schema](../) 定義語言 (XSD) 架構是否已編譯。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 傳回 [XmlSchemaSet](./) 在載入新 XML [Schema](../) 定義語言 (XSD) 架構時使用的預設 [XmlNameTable](../../system.xml/xmlnametable/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標型別描述的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 安全物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Remove](./remove/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 從 [XmlSchemaSet](./) 中移除指定的 XML [Schema](../) 定義語言 (XSD) 架構。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| **bool** [RemoveRecursive](./removerecursive/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 從 [XmlSchemaSet](./) 中移除指定的 XML [Schema](../) 定義語言 (XSD) 架構以及它所匯入的所有架構。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [Reprocess](./reprocess/)([SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>) | 重新處理已存在於 [XmlSchemaSet](./) 中的 XML [Schema](../) 定義語言 (XSD) 架構。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IList](../../system.collections.generic/ilist/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)() | 傳回 [XmlSchemaSet](./) 中所有 XML [Schema](../) 定義語言 (XSD) 架構的集合。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::List](../../system.collections.generic/list/)\<[SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\>\> [Schemas](./schemas/)([String](../../system/string/)) | 傳回屬於給定命名空間的 [XmlSchemaSet](./) 中所有 XML [Schema](../) 定義語言 (XSD) 架構的集合。 |
| void [set_CompilationSettings](./set_compilationsettings/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)\>\&) | 設定 [XmlSchemaSet](./) 的 [XmlSchemaCompilationSettings](../xmlschemacompilationsettings/)。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | 設定用於解析架構中 include 和 import 元素所引用的命名空間或位置的 [XmlResolver](../../system.xml/xmlresolver/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 安全物件。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | 加入事件處理常式，以接收有關 XML [Schema](../) 定義語言 (XSD) 架構驗證錯誤的資訊。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | 移除事件處理常式，以停止接收有關 XML [Schema](../) 定義語言 (XSD) 架構驗證錯誤的資訊。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
|  [XmlSchemaSet](./xmlschemaset/)() | 初始化 [XmlSchemaSet](./) 類別的新執行個體。 |
|  [XmlSchemaSet](./xmlschemaset/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>\&) | 以指定的 [XmlNameTable](../../system.xml/xmlnametable/) 初始化 [XmlSchemaSet](./) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 備註

此類別的物件僅應使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 运算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Xml::Schema](../)
* 程式庫 [Aspose.Slides](../../)