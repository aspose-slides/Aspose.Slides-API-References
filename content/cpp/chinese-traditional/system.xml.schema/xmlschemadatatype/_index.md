---
title: XmlSchemaDatatype
second_title: Aspose.Slides for C++ API 參考
description: XmlSchemaDatatype 類別是抽象類別，用於將 XML Schema 定義語言 (XSD) 類型對映到執行期類型。
type: docs
weight: 339
url: /zh-hant/system.xml.schema/xmlschemadatatype/
---
## XmlSchemaDatatype 類別


[XmlSchemaDatatype](./) 類別是抽象類別，用於將 XML [Schema](../) 定義語言 (XSD) 類型對映到執行期類型。

```cpp
class XmlSchemaDatatype : public System::Object
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&) | 將指定的值（其類型是由 [XmlSchemaDatatype](./) 所代表的 XML 架構類型的有效表示之一）轉換為指定的執行期類型。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ChangeType](./changetype/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 將指定的值（其類型是由 [XmlSchemaDatatype](./) 所代表的 XML 架構類型的有效表示之一）轉換為執行期類型；如果 [XmlSchemaDatatype](./) 代表 **xs:QName** 類型或其衍生類型，則使用 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [XmlTokenizedType](../../system.xml/xmltokenizedtype/) [get_TokenizedType](./get_tokenizedtype/)() | 在衍生類別中覆寫時，取得 **string** 的類型，此類型依據 World Wide [Web](../../system.web/) Consortium (W3C) XML 1.0 規範所指定。 |
| virtual [XmlTypeCode](../xmltypecode/) [get_TypeCode](./get_typecode/)() | 傳回簡單型別的 XmlTypeCode 值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | 在衍生類別中覆寫時，取得項目的類型。 |
| virtual [XmlSchemaDatatypeVariety](../xmlschemadatatypevariety/) [get_Variety](./get_variety/)() | 傳回簡單型別的 XmlSchemaDatatypeVariety 值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 'is' 運算子。 |
| virtual **bool** [IsDerivedFrom](./isderivedfrom/)([SharedPtr](../../system/sharedptr/)\<[XmlSchemaDatatype](./)\>) | 此方法永遠傳回 **false**。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許為子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許為子類別進行複製建構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ParseValue](./parsevalue/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\>, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 在衍生類別中覆寫時，驗證指定的 **string** 是否符合內建或使用者自訂的簡單型別。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於 string 與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 構造式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 類型定義

| 類型別名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此類別之實例的共享指標別名。 |

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Xml::Schema](../)
* 函式庫 [Aspose.Slides](../../)