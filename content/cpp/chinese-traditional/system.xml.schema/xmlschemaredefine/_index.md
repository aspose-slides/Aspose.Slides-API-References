---
title: XmlSchemaRedefine
second_title: Aspose.Slides for C++ API 參考
description: 此類別表示 XML Schema 中的 redefine 元素，遵循萬維網聯盟 (W3C) 的規範。可用於允許來自外部結構描述檔的簡單和複雜型別、群組以及屬性群組在目前的結構描述檔中重新定義。此類別亦可用於為結構描述檔元素提供版本控制。
type: docs
weight: 755
url: /zh-hant/system.xml.schema/xmlschemaredefine/
---
## XmlSchemaRedefine 類別


表示 XML [Schema](../) 中的 **redefine** 元素，符合由 World Wide [Web](../../system.web/) Consortium (W3C) 所指定的規範。此類別可用於允許外部結構描述檔中的簡單與複雜型別、群組以及屬性群組在目前的結構描述檔中重新定義。此類別亦可用於為結構描述檔元素提供版本控制。

```cpp
class XmlSchemaRedefine : public System::Xml::Schema::XmlSchemaExternal
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，儘管根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeGroups](./get_attributegroups/)() | 傳回 [XmlSchemaObjectTable](../xmlschemaobjecttable/)，針對結構描述檔中所有屬性，該值保留 **AttributeGroups** 的編譯後解釋。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_Groups](./get_groups/)() | 傳回 [XmlSchemaObjectTable](../xmlschemaobjecttable/)，針對結構描述檔中所有群組，該值保留 **Groups** 的編譯後解釋。 |
| [String](../../system/string/) [get_Id](../xmlschemaexternal/get_id/)() | 傳回字串 id。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Items](./get_items/)() | 傳回以下類別的集合：[XmlSchemaAnnotation](../xmlschemaannotation/)、[XmlSchemaAttributeGroup](../xmlschemaattributegroup/)、[XmlSchemaComplexType](../xmlschemacomplextype/)、[XmlSchemaSimpleType](../xmlschemasimpletype/) 與 [XmlSchemaGroup](../xmlschemagroup/)。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 傳回 **schema** 元素所參考檔案中的行號。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 傳回 **schema** 元素所參考檔案中的列位置。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 傳回用於此結構描述檔物件的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 傳回此 [XmlSchemaObject](../xmlschemaobject/) 的父項。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\> [get_Schema](../xmlschemaexternal/get_schema/)() | 傳回參考結構描述檔的 [XmlSchema](../xmlschema/)。 |
| [String](../../system/string/) [get_SchemaLocation](../xmlschemaexternal/get_schemalocation/)() | 傳回結構描述檔的統一資源識別碼 (URI) 位置，告訴結構描述檔處理器結構描述檔的實際所在位置。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_SchemaTypes](./get_schematypes/)() | 傳回 [XmlSchemaObjectTable](../xmlschemaobjecttable/)，針對結構描述檔中所有簡單與複雜型別，該值保留 **SchemaTypes** 的編譯後解釋。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 傳回載入結構描述檔之檔案的來源位置。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaexternal/get_unhandledattributes/)() | 傳回已限定的屬性，這些屬性不屬於結構描述檔的目標命名空間。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。C# [System.Object.GetType()](../../system/object/gettype/) 呼叫的類似功能。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類似功能。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構式。實際上不會複製任何東西，只是初始化新物件並允許為子類別進行拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許為子類別進行拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [set_Id](../xmlschemaexternal/set_id/)(const [String](../../system/string/)\&) | 設定字串 id。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 設定 **schema** 元素所參考檔案中的行號。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 設定 **schema** 元素所參考檔案中的列位置。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 設定用於此結構描述檔物件的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 設定此 [XmlSchemaObject](../xmlschemaobject/) 的父項。 |
| void [set_Schema](../xmlschemaexternal/set_schema/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchema](../xmlschema/)\>\&) | 設定參考結構描述檔的 [XmlSchema](../xmlschema/)。 |
| void [set_SchemaLocation](../xmlschemaexternal/set_schemalocation/)(const [String](../../system/string/)\&) | 設定結構描述檔的統一資源識別碼 (URI) 位置，告訴結構描述檔處理器結構描述檔的實際所在位置。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 設定載入結構描述檔之檔案的來源位置。 |
| void [set_UnhandledAttributes](../xmlschemaexternal/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 設定已限定的屬性，這些屬性不屬於結構描述檔的目標命名空間。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享指標）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類似功能。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlSchemaExternal](../xmlschemaexternal/xmlschemaexternal/)() | 初始化 [XmlSchemaExternal](../xmlschemaexternal/) 類別的新實例。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 類別的新實例。 |
|  [XmlSchemaRedefine](./xmlschemaredefine/)() | 初始化 [XmlSchemaRedefine](./) 類別的新實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 備註



此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標作為參數傳遞給函式。 

## 另請參閱

* 類別 [XmlSchemaExternal](../xmlschemaexternal/)
* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)