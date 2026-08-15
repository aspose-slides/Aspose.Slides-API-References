---
title: XmlNodeReader
second_title: Aspose.Slides for C++ API 參考文件
description: 代表一個閱讀器，可提供快速、非快取的僅向前存取 XmlNode 中的 XML 資料。
type: docs
weight: 365
url: /zh-hant/system.xml/xmlnodereader/
---
## XmlNodeReader 類別


表示一個讀取器，提供對 [XmlNode](../xmlnode/) 中 XML 資料的快速、非快取、僅向前存取。

```cpp
class XmlNodeReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Close](./close/)() override | 將 [XmlNodeReader::get_ReadState](./get_readstate/) 更改為 [ReadState::Closed](../readstate/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 建立具有指定 URI 的新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 與設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、設定和解析的上下文資訊建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的串流與預設設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的串流與設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的串流、基礎 URI 與設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的串流、設定及解析的上下文資訊建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文字讀取器建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文字讀取器與設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文字讀取器、設定與基礎 URI 建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文字讀取器、設定與解析的上下文資訊建立新的 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 讀取器與設定建立新的 [XmlReader](../xmlreader/) 實例。 |
| void [Dispose](../xmlreader/dispose/)() override | 釋放目前 [XmlReader](../xmlreader/) 類別實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值（包括 NaN）。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 傳回目前節點的屬性數量。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 傳回目前節點的基礎 URI。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | 傳回指示 [XmlNodeReader](./) 是否實作二進位內容讀取方法的值。 |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | 傳回指示 [XmlReader](../xmlreader/) 是否實作 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 方法的值。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 傳回指示此讀取器是否能解析與解析實體的值。 |
| **int32_t** [get_Depth](./get_depth/)() override | 傳回 XML 文件中目前節點的深度。 |
| **bool** [get_EOF](./get_eof/)() override | 傳回指示讀取器是否位於串流結尾的值。 |
| **bool** [get_HasAttributes](./get_hasattributes/)() override | 傳回指示目前節點是否具有任何屬性的值。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 傳回指示目前節點是否可以具有 [XmlNodeReader::get_Value](./get_value/) 值的值。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 傳回指示目前節點是否為從文件類型定義 (DTD) 或綱要中定義的預設值產生的屬性的值。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 傳回指示目前節點是否為空元素 (例如 **<MyElement/>**) 的值。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 傳回目前節點的本地名稱。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 傳回目前節點的限定名稱。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 傳回讀取器所在節點的命名空間 URI（依 W3C 命名空間規範定義）。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 傳回與此實作相關聯的 [XmlNameTable](../xmlnametable/)。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 傳回目前節點的類型。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 傳回與目前節點相關聯的命名空間前綴。 |
| virtual char16_t [get_QuoteChar](../xmlreader/get_quotechar/)() | 在衍生類別中覆寫時，取得用於包圍屬性節點值的引號字元。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 傳回讀取器的狀態。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | 傳回已指派給目前節點的綱要資訊。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 傳回用於建立此 [XmlReader](../xmlreader/) 實例的 [XmlReaderSettings](../xmlreadersettings/) 物件。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 傳回目前節點的文字值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 傳回目前節點的類型。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 傳回目前的 **xml:lang** 範圍。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 傳回目前的 **xml:space** 範圍。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 傳回具有指定名稱的屬性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 傳回具有指定本地名稱及命名空間 URI 的屬性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 傳回具有指定索引的屬性值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 在衍生類別中覆寫時，取得具有指定索引的屬性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](../xmlreader/get_name/) 值的屬性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的屬性值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 描述的類型實例。相當於 C# 的 'is' 運算子。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 傳回指示字串參數是否為有效 XML 名稱的值。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 傳回指示字串參數是否為有效 XML 名稱標記的值。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 並測試目前內容節點是否為開始標籤或空元素標籤。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 並測試目前內容節點是否為開始標籤或空元素標籤，且找到的元素之 [XmlReader::get_Name](../xmlreader/get_name/) 值是否與給定參數相符。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 並測試目前內容節點是否為開始標籤或空元素標籤，且找到的元素之 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否與給定字串相符。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 在目前元素的範圍內解析命名空間前綴。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 移動至具有指定名稱的屬性。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 移動至具有指定本地名稱與命名空間 URI 的屬性。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 移動至具有指定索引的屬性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 檢查目前節點是否為內容節點（非空白文字、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果節點不是內容節點，讀取器會跳過至下一個內容節點或檔案結尾。它會跳過以下類型的節點：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 移動至包含目前屬性節點的元素。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 移動至第一個屬性。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 移動至下一個屬性。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| **bool** [Read](./read/)() override | 從串流讀取下一個節點。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 將屬性值解析為一個或多個 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將內容讀取為指定型別的物件。 |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取內容並傳回 Base64 解碼後的二進位位元組。 |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取內容並傳回 BinHex 解碼後的二進位位元組。 |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | 將目前位置的文字內容讀取為 [Boolean](../../system/boolean/)。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | 將目前位置的文字內容讀取為 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | 將目前位置的文字內容讀取為 [DateTimeOffset](../../system/datetimeoffset/) 物件。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | 將目前位置的文字內容讀取為 [Decimal](../../system/decimal/) 物件。 |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | 將目前位置的文字內容讀取為雙精度浮點數。 |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | 將目前位置的文字內容讀取為單精度浮點數。 |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | 將目前位置的文字內容讀取為 32 位元帶符號整數。 |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | 將目前位置的文字內容讀取為 64 位元帶符號整數。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | 將目前位置的文字內容讀取為 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | 在目前位置讀取文字內容，並以 [String](../../system/string/) 物件的形式返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將元素內容讀取為指定的類型。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後將元素內容讀取為指定的類型。 |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取元素並解碼 Base64 內容。 |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取元素並解碼 BinHex 內容。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 讀取當前元素，並將內容作為 [Boolean](../../system/boolean/) 物件返回。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 [Boolean](../../system/boolean/) 物件返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 讀取當前元素，並將內容作為 [DateTime](../../system/datetime/) 物件返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 [DateTime](../../system/datetime/) 物件返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 讀取當前元素，並將內容作為 [Decimal](../../system/decimal/) 物件返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 [Decimal](../../system/decimal/) 物件返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 讀取當前元素，並將內容作為雙精度浮點數返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為雙精度浮點數返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 讀取當前元素，並將內容作為單精度浮點數返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為單精度浮點數返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 讀取當前元素，並將內容作為 32 位元有號整數返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 32 位元有號整數返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 讀取當前元素，並將內容作為 64 位元有號整數返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 64 位元有號整數返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 讀取當前元素，並將內容作為 [Object](../../system/object/) 物件返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 [Object](../../system/object/) 物件返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 讀取當前元素，並將內容作為 [String](../../system/string/) 物件返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取當前元素，並將內容作為 [String](../../system/string/) 物件返回。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | 讀取僅包含文字的元素。然而，建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | 在讀取僅文字元素之前，先檢查找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否與給定字串相符。然而，建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 在讀取僅文字元素之前，先檢查找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否與給定字串相符。然而，建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 檢查目前的內容節點是否為結束標記，然後將閱讀器前進到下一個節點。 |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 在衍生類別中覆寫時，將所有內容（包括標記）讀取為字串。 |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 在衍生類別中覆寫時，讀取代表此節點及其所有子節點的內容（包括標記）。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 檢查目前的節點是否為元素，然後將閱讀器前進到下一個節點。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 檢查目前的內容節點是否為具有給定 [XmlReader::get_Name](../xmlreader/get_name/) 值的元素，然後將閱讀器前進到下一個節點。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 檢查目前的內容節點是否為具有給定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的元素，然後將閱讀器前進到下一個節點。 |
| [String](../../system/string/) [ReadString](./readstring/)() override | 將元素或文字節點的內容讀取為字串。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 返回一個新的 [XmlReader](../xmlreader/) 實例，可用於讀取當前節點及其所有子節點。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定限定名稱的下一個子孫元素。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定本地名稱和命名空間 URI 的下一個子孫元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 持續讀取，直到找到具有指定限定名稱的元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 持續讀取，直到找到具有指定本地名稱和命名空間 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定限定名稱的下一個同層元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定本地名稱和命名空間 URI 的下一個同層元素。 |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 讀取嵌入於 XML 文件中的大段文字流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [ResolveEntity](./resolveentity/)() override | 解析 **EntityReference** 節點的實體參考。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的當前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [Skip](./skip/)() override | 跳過當前節點的子節點。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# 的 [Object.ToString()](../../system/object/tostring/) 方法。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# 的 typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監護物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫，請改用智慧指標或 ThisProtector。 |
|  [XmlNodeReader](./xmlnodereader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | 使用指定的 [XmlNode](../xmlnode/) 建立 [XmlNodeReader](./) 類別的實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例之共享指標的別名。 |

## 備註

此類別的物件應僅透過 [System::MakeObject()](../../system/makeobject/) 函式進行配置。切勿在堆疊上或使用 operator new 建立此類型的實例，因為這會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用此指標將其作為參數傳遞給函式。

## 另請參閱

* 類別 [XmlReader](../xmlreader/)
* 類別 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)