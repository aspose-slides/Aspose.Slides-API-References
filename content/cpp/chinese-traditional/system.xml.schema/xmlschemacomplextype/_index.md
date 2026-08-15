---
title: XmlSchemaComplexType
second_title: Aspose.Slides for C++ API 參考
description: 代表 W3C（World Wide Web Consortium）所規範的 XML Schema 中的 complexType 元素。此類別定義了一種複雜型別，決定元素的屬性和內容集合。
type: docs
weight: 300
url: /zh-hant/system.xml.schema/xmlschemacomplextype/
---
## XmlSchemaComplexType 類別


表示 **complexType** 元素（來自 XML [Schema](../)），依 World Wide [Web](../../system.web/) Consortium (W3C) 規範。本類別定義了一個複雜類型，以確定元素的屬性和內容集合。

```cpp
class XmlSchemaComplexType : public System::Xml::Schema::XmlSchemaType
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\> [get_Annotation](../xmlschemaannotated/get_annotation/)() | 傳回 **annotation** 屬性。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AnyAttribute](./get_anyattribute/)() | 傳回複雜型別的 [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) 元件的值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectCollection](../xmlschemaobjectcollection/)\> [get_Attributes](./get_attributes/)() | 傳回此複雜型別的屬性集合。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObjectTable](../xmlschemaobjecttable/)\> [get_AttributeUses](./get_attributeuses/)() | 傳回此複雜型別及其基底型別的所有已編譯屬性集合。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\> [get_AttributeWildcard](./get_attributewildcard/)() | 傳回此複雜型別及其基底型別的 **anyAttribute** 後編譯值。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_BaseSchemaType](../xmlschematype/get_baseschematype/)() | 傳回後編譯的物件類型或內建 XML [Schema](../) 定義語言 (XSD) 資料型別、simpleType 元素或 complexType 元素。這是後綱要編譯資訊集的值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\> [get_BaseXmlSchemaType](../xmlschematype/get_basexmlschematype/)() | 傳回此綱要型別基底型別的後編譯值。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Block](./get_block/)() | 傳回 **block** 屬性。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_BlockResolved](./get_blockresolved/)() | 傳回型別編譯為後綱要驗證資訊集 (infoset) 後的值。此值指出在實例文件中使用 **xsi:type** 時型別的強制方式。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\> [get_ContentModel](./get_contentmodel/)() | 傳回此複雜型別的後編譯 [XmlSchemaContentModel](../xmlschemacontentmodel/)。 |
| [XmlSchemaContentType](../xmlschemacontenttype/) [get_ContentType](./get_contenttype/)() | 傳回此複雜型別的內容模型，其中包含後編譯值。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_ContentTypeParticle](./get_contenttypeparticle/)() | 傳回持有 [XmlSchemaComplexType::get_ContentType](./get_contenttype/) 粒子的後編譯值的粒子。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](../xmlschemadatatype/)\> [get_Datatype](../xmlschematype/get_datatype/)() | 傳回此複雜型別資料型別的後編譯值。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_DerivedBy](../xmlschematype/get_derivedby/)() | 傳回此元素如何從其基底型別衍生的後編譯資訊。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_Final](../xmlschematype/get_final/)() | 傳回型別衍生的最終屬性，指示是否允許進一步的衍生。 |
| [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/) [get_FinalResolved](../xmlschematype/get_finalresolved/)() | 傳回 [XmlSchemaType::get_Final](../xmlschematype/get_final/) 值的後編譯詮釋。 |
| [String](../../system/string/) [get_Id](../xmlschemaannotated/get_id/)() | 傳回字串 ID。 |
| **bool** [get_IsAbstract](./get_isabstract/)() | 傳回決定 **complexType** 元素是否可在實例文件中使用的資訊。 |
| **bool** [get_IsMixed](./get_ismixed/)() override | 傳回決定複雜型別是否具有混合內容模型（內容內的標記）的資訊。 |
| **int32_t** [get_LineNumber](../xmlschemaobject/get_linenumber/)() | 傳回 **schema** 元素所指向檔案的行號。 |
| **int32_t** [get_LinePosition](../xmlschemaobject/get_lineposition/)() | 傳回 **schema** 元素所指向檔案的列位置。 |
| [String](../../system/string/) [get_Name](../xmlschematype/get_name/)() | 傳回型別的名稱。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\> [get_Namespaces](../xmlschemaobject/get_namespaces/)() | 傳回此綱要物件使用的 XmlSerializerNamespaces。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\> [get_Parent](../xmlschemaobject/get_parent/)() | 傳回此 [XmlSchemaObject](../xmlschemaobject/) 的父項目。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\> [get_Particle](./get_particle/)() | 傳回合成器型別，為 [XmlSchemaGroupRef](../xmlschemagroupref/)、[XmlSchemaChoice](../xmlschemachoice/)、[XmlSchemaAll](../xmlschemaall/) 或 [XmlSchemaSequence](../xmlschemasequence/) 類別之一。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_QualifiedName](../xmlschematype/get_qualifiedname/)() | 傳回根據此型別的 **Name** 屬性建構的合格名稱。這是後綱要編譯值。 |
| [String](../../system/string/) [get_SourceUri](../xmlschemaobject/get_sourceuri/)() | 傳回載入綱要之檔案的來源位置。 |
| [XmlTypeCode](../xmltypecode/) [get_TypeCode](../xmlschematype/get_typecode/)() | 傳回此型別的 XmlTypeCode。 |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\> [get_UnhandledAttributes](../xmlschemaannotated/get_unhandledattributes/)() | 傳回不屬於目前綱要目標命名空間的合格屬性。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)([XmlTypeCode](../xmltypecode/)) | 傳回表示指定複雜型別之內建複雜型別的 [XmlSchemaComplexType](./)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaComplexType](./)\> [GetBuiltInComplexType](../xmlschematype/getbuiltincomplextype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 傳回表示由合格名稱指定之複雜型別的內建複雜型別的 [XmlSchemaComplexType](./)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)(const [SharedPtr](../../system/sharedptr/)\<[XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>\&) | 傳回表示由合格名稱指定之簡單型別的內建簡單型別的 [XmlSchemaSimpleType](../xmlschemasimpletype/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlSchemaSimpleType](../xmlschemasimpletype/)\> [GetBuiltInSimpleType](../xmlschematype/getbuiltinsimpletype/)([XmlTypeCode](../xmltypecode/)) | 傳回表示指定簡單型別之內建簡單型別的 [XmlSchemaSimpleType](../xmlschemasimpletype/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述型別的實例。相當於 C# 的 'is' 運算子。 |
| static **bool** [IsDerivedFrom](../xmlschematype/isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaType](../xmlschematype/)\>\&, [XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 傳回一個值，指示指定的衍生綱要型別是否衍生自指定的基底綱要型別。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只是初始化新物件並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Annotation](../xmlschemaannotated/set_annotation/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnnotation](../xmlschemaannotation/)\>\&) | 設定 **annotation** 屬性。 |
| void [set_AnyAttribute](./set_anyattribute/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaAnyAttribute](../xmlschemaanyattribute/)\>\&) | 設定複雜型別的 [XmlSchemaAnyAttribute](../xmlschemaanyattribute/) 元件的值。 |
| void [set_Block](./set_block/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 設定 **block** 屬性。 |
| void [set_ContentModel](./set_contentmodel/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaContentModel](../xmlschemacontentmodel/)\>\&) | 設定此複雜型別的後編譯 [XmlSchemaContentModel](../xmlschemacontentmodel/)。 |
| void [set_Final](../xmlschematype/set_final/)([XmlSchemaDerivationMethod](../xmlschemaderivationmethod/)) | 設定型別衍生的最終屬性，指示是否允許進一步的衍生。 |
| void [set_Id](../xmlschemaannotated/set_id/)(const [String](../../system/string/)\&) | 設定字串 ID。 |
| void [set_IsAbstract](./set_isabstract/)(**bool**) | 設定決定 **complexType** 元素是否可在實例文件中使用的資訊。 |
| void [set_IsMixed](./set_ismixed/)(**bool**) override | 設定決定複雜型別是否具有混合內容模型（內容內的標記）的資訊。 |
| void [set_LineNumber](../xmlschemaobject/set_linenumber/)(**int32_t**) | 設定 **schema** 元素所指向檔案的行號。 |
| void [set_LinePosition](../xmlschemaobject/set_lineposition/)(**int32_t**) | 設定 **schema** 元素所指向檔案的列位置。 |
| void [set_Name](../xmlschematype/set_name/)(const [String](../../system/string/)\&) | 設定型別的名稱。 |
| void [set_Namespaces](../xmlschemaobject/set_namespaces/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::Serialization::XmlSerializerNamespaces](../../system.xml.serialization/xmlserializernamespaces/)\>\&) | 設定此綱要物件使用的 XmlSerializerNamespaces。 |
| void [set_Parent](../xmlschemaobject/set_parent/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaObject](../xmlschemaobject/)\>\&) | 設定此 [XmlSchemaObject](../xmlschemaobject/) 的父項目。 |
| void [set_Particle](./set_particle/)(const [SharedPtr](../../system/sharedptr/)\<[XmlSchemaParticle](../xmlschemaparticle/)\>\&) | 設定合成器型別為 [XmlSchemaGroupRef](../xmlschemagroupref/)、[XmlSchemaChoice](../xmlschemachoice/)、[XmlSchemaAll](../xmlschemaall/) 或 [XmlSchemaSequence](../xmlschemasequence/) 類別之一。 |
| void [set_SourceUri](../xmlschemaobject/set_sourceuri/)(const [String](../../system/string/)\&) | 設定載入綱要之檔案的來源位置。 |
| void [set_UnhandledAttributes](../xmlschemaannotated/set_unhandledattributes/)(const [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../../system.xml/xmlattribute/)\>\>\&) | 設定不屬於目前綱要目標命名空間的合格屬性。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlSchemaComplexType](./xmlschemacomplextype/)() | 初始化 [XmlSchemaComplexType](./) 類別的新執行個體。 |
|  [XmlSchemaObject](../xmlschemaobject/xmlschemaobject/)() | 初始化 [XmlSchemaObject](../xmlschemaobject/) 類別的新執行個體。 |
|  [XmlSchemaType](../xmlschematype/xmlschematype/)() | 初始化 [XmlSchemaType](../xmlschematype/) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別之實例的共享指標別名。 |

## 備註



此類別的物件應該僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此型別的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。 

## 另請參閱

* 類別 [XmlSchemaType](../xmlschematype/)
* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)