---
title: XmlSchemaAttribute
second_title: Aspose.Slides for C++ API 參考文件
description: 代表由全球資訊網聯盟（W3C）所規範的 XML Schema 中的 attribute 元素。屬性為其他文件元素提供額外資訊。屬性標籤位於文件元素的標籤之間，用於 schema。XML 文件在元素的起始標籤中將屬性顯示為具名項目。
type: docs
weight: 170
url: /zh-hant/system.xml.schema/xmlschemaattribute/
---
## XmlSchemaAttribute 類別

表示 XML [Schema](../) 中的 **屬性** 元素，根據全球 [Web](../../system.web/) 聯盟 (W3C) 的規範。屬性為其他文件元素提供額外資訊。屬性標籤位於結構文件元素的標籤之間。XML 文件在元素的開啟標籤中將屬性顯示為具名項目。

```cpp
class XmlSchemaAttribute : public System::Xml::Schema::XmlSchemaAnnotated
```

## 方法

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | 傳回 **annotation** 屬性。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_AttributeSchemaType](./get_attributeschematype/)() | 傳回一個 [XmlSchemaSimpleType](../xmlschemasimpletype/) 物件，代表根據屬性的 [XmlSchemaAttribute::get_SchemaType](./get_schematype/) 或 [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) 值的屬性類型。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_AttributeType](./get_attributetype/)() | 傳回基於屬性的 [XmlSchemaAttribute::get_SchemaType](./get_schematype/) 或 [XmlSchemaAttribute::get_SchemaTypeName](./get_schematypename/) 值的物件，該值保存 **AttributeType** 的編譯後詮釋。 |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | 傳回屬性的預設值。 |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | 傳回屬性的固定值。 |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | 傳回屬性的形式。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 傳回字串 ID。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 傳回 **schema** 元素所參照檔案中的行號。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 傳回 **schema** 元素所參照檔案中的行位置。 |
| [String](../../system/string/) [get_Name](./get_name/)() | 傳回屬性的名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 傳回用於此 **schema** 物件的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 傳回此 [XmlSchemaObject](../xmlschemaobject/) 的父項。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | 傳回屬性的限定名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | 傳回在此 **schema**（或指定命名空間指示的其他 **schema**）中宣告的屬性名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [get_SchemaType](./get_schematype/)() | 傳回屬性類型為簡單型別。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | 傳回此 **schema**（或指定命名空間指示的其他 **schema**）中定義的簡單型別名稱。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 傳回載入此 **schema** 的檔案之來源位置。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 傳回不屬於目前 **schema** 目標命名空間的限定屬性。 |
| [XmlSchemaUse](../xmlschemause/) [get_Use](./get_use/)() | 傳回屬性的使用方式資訊。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 類似 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。類似 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。類似 C# 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 類似 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串與 nullptr 情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的專門化，用於字串情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參考計數減少指定的值。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | 設定 **annotation** 屬性。 |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | 設定屬性的預設值。 |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | 設定屬性的固定值。 |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | 設定屬性的形式。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 設定字串 ID。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 設定 **schema** 元素所參照檔案的行號。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 設定 **schema** 元素所參照檔案的行位置。 |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | 設定屬性的名稱。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 設定此 **schema** 物件使用的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 設定此 [XmlSchemaObject](../xmlschemaobject/) 的父項。 |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 設定在此 **schema**（或指定命名空間指示的其他 **schema**）中宣告的屬性名稱。 |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\>\&) | 設定屬性類型為簡單型別。 |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 設定此 **schema**（或指定命名空間指示的其他 **schema**）中定義的簡單型別名稱。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 設定載入此 **schema** 的檔案之來源位置。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 設定不屬於目前 **schema** 目標命名空間的限定屬性。 |
| void [set_Use](./set_use/)([XmlSchemaUse](../xmlschemause/)) | 設定屬性的使用方式資訊。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共用指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共用參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共用參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 類似 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlSchemaAttribute](./xmlschemaattribute/)() | 初始化 [XmlSchemaAttribute](./) 類別的新執行個體。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 備註

此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別包裹在 [System::SmartPtr](../../system/smartptr/) 指標中，並使用該指標將其作為參數傳遞給函式。

## 另請參閱

* 類別 [XmlSchemaAnnotated](../xmlschemaannotated/)
* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)