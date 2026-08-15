---
title: XmlSchemaElement
second_title: Aspose.Slides for C++ API 參考文件
description: 表示符合全球資訊網協會 (W3C) 規範的 XML Schema 中的 element 元素。此類別是所有粒子類型的基底類別，用於描述 XML 文件中的元素。
type: docs
weight: 365
url: /zh-hant/system.xml.schema/xmlschemaelement/
---
## XmlSchemaElement 類別

代表 XML [Schema](../) 中的 **element** 元素，該元素遵循全球資訊網 [Web](../../system.web/) 組織 (W3C) 的規範。此 類別 是所有粒子類型的基類，用於描述 XML 文件中的元素。

```cpp
class XmlSchemaElement : public System::Xml::Schema::XmlSchemaParticle
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意來比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，儘管根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | 傳回 **annotation** 屬性。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | 傳回 **Block** 派生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | 傳回 **Block** 值的編譯後詮釋。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Constraints](./get_constraints/)() | 傳回元素的限制集合。 |
| [String](../../system/string/) [get_DefaultValue](./get_defaultvalue/)() | 如果元素的內容是簡單類型或元素的內容是 **textOnly**，則傳回元素的預設值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_ElementSchemaType](./get_elementschematype/)() | 傳回一個 [XmlSchemaType](../xmlschematype/) 物件，表示根據元素的 [XmlSchemaElement::get_SchemaType](./get_schematype/) 或 [XmlSchemaElement::get_SchemaTypeName](./get_schematypename/) 值的元素類型。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_ElementType](./get_elementtype/)() | 傳回一個依據元素的 [XmlSchemaElement](./) 或 [XmlSchemaElement](./) 的物件，該物件包含 **ElementType** 值的編譯後詮釋。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](./get_final/)() | 傳回 **Final** 值，以表示不再允許其他派生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](./get_finalresolved/)() | 傳回 **Final** 值的編譯後詮釋。 |
| [String](../../system/string/) [get_FixedValue](./get_fixedvalue/)() | 傳回固定值。 |
| [XmlSchemaForm](../xmlschemaform/) [get_Form](./get_form/)() | 傳回元素的形式。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 傳回字串 ID。 |
| **bool** [get_IsAbstract](./get_isabstract/)() | 傳回資訊，用以指示此元素是否可在實例文件中使用。 |
| **bool** [get_IsNillable](./get_isnillable/)() | 傳回資訊，指出 **xsi:nil** 是否可以出現在實例資料中。亦表示是否可將明確的 nil 值指派給此元素。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 傳回 **schema** 元素所參照檔案的行號。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 傳回 **schema** 元素所參照檔案的行位置。 |
| [Decimal](../../system/decimal/) [get_MaxOccurs](../xmlschemaparticle/get_maxoccurs/)() | 傳回粒子可出現的最大次數。 |
| [String](../../system/string/) [get_MaxOccursString](../xmlschemaparticle/get_maxoccursstring/)() | 傳回以字串形式表示的數字。粒子可出現的最大次數。 |
| [Decimal](../../system/decimal/) [get_MinOccurs](../xmlschemaparticle/get_minoccurs/)() | 傳回粒子可出現的最小次數。 |
| [String](../../system/string/) [get_MinOccursString](../xmlschemaparticle/get_minoccursstring/)() | 傳回以字串形式表示的數字。粒子可出現的最小次數。 |
| [String](../../system/string/) [get_Name](./get_name/)() | 傳回元素的名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 傳回用於此 schema 物件的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 傳回此 [XmlSchemaObject](../xmlschemaobject/) 的父項目。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](./get_qualifiedname/)() | 傳回給定元素的實際限定名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_RefName](./get_refname/)() | 傳回在此 schema（或指定命名空間所指的其他 schema）中聲明的元素的參考名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_SchemaType](./get_schematype/)() | 傳回元素的類型。此類型可以是複雜類型或簡單類型。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SchemaTypeName](./get_schematypename/)() | 傳回此 schema（或指定命名空間所指的其他 schema）中定義的內建資料類型名稱。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 傳回載入此 schema 的檔案之來源位置。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_SubstitutionGroup](./get_substitutiongroup/)() | 傳回此元素所取代的元素名稱。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 傳回不屬於目前 schema 目標命名空間的限定屬性。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式之鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
| [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別進行複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 將值型別物件與 nullptr 以參考方式比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 對字串與 nullptr 情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 對字串情況的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值減少共享參考計數。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | 設定 **annotation** 屬性。 |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 設定 **Block** 派生。 |
| void [set_DefaultValue](./set_defaultvalue/)(const [String](../../system/string/)\&) | 如果元素的內容是簡單類型或元素的內容是 **textOnly**，則設定其預設值。 |
| void [set_Final](./set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 設定 **Final** 值，以表示不允許進一步的派生。 |
| void [set_FixedValue](./set_fixedvalue/)(const [String](../../system/string/)\&) | 設定固定值。 |
| void [set_Form](./set_form/)([XmlSchemaForm](../xmlschemaform/)) | 設定元素的形式。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 設定字串 ID。 |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | 設定資訊，用以指示此元素是否可在實例文件中使用。 |
| void [set_IsNillable](./set_isnillable/)(**bool**) | 設定資訊，指出 **xsi:nil** 是否可以出現在實例資料中。亦表示是否可將明確的 nil 值指派給此元素。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 設定 **schema** 元素所參照檔案的行號。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 設定 **schema** 元素所參照檔案的行位置。 |
| void [set_MaxOccurs](../xmlschemaparticle/set_maxoccurs/)([Decimal](../../system/decimal/)) | 設定粒子可出現的最大次數。 |
| void [set_MaxOccursString](../xmlschemaparticle/set_maxoccursstring/)(const [String](../../system/string/)\&) | 設定以字串形式表示的數字。粒子可出現的最大次數。 |
| void [set_MinOccurs](../xmlschemaparticle/set_minoccurs/)([Decimal](../../system/decimal/)) | 設定粒子可出現的最小次數。 |
| void [set_MinOccursString](../xmlschemaparticle/set_minoccursstring/)(const [String](../../system/string/)\&) | 設定以字串形式表示的數字。粒子可出現的最小次數。 |
| void [set_Name](./set_name/)(const [String](../../system/string/)\&) | 設定元素的名稱。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 設定用於此 schema 物件的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 設定此 [XmlSchemaObject](../xmlschemaobject/) 的父項目。 |
| void [set_RefName](./set_refname/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 設定在此 schema（或指定命名空間所指的其他 schema）中聲明的元素的參考名稱。 |
| void [set_SchemaType](./set_schematype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&) | 設定元素的類型。此類型可以是複雜類型或簡單類型。 |
| void [set_SchemaTypeName](./set_schematypename/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 設定此 schema（或指定命名空間所指的其他 schema）中定義的內建資料類型名稱。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 設定載入此 schema 的檔案之來源位置。 |
| void [set_SubstitutionGroup](./set_substitutiongroup/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 設定此元素所取代的元素名稱。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 設定不屬於目前 schema 目標命名空間的限定屬性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式之解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [XmlSchemaElement](./xmlschemaelement/)() | 初始化 [XmlSchemaElement](./) 類別的新執行個體。 |
| [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 類別的新執行個體。 |
| [XmlSchemaParticle](../xmlschemaparticle/xmlschemaparticle/)() | 初始化 [XmlSchemaParticle](../xmlschemaparticle/) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別之實例的共享指標別名。 |

## 備註

此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 參見

* 類別 [XmlSchemaParticle](../xmlschemaparticle/)
* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)