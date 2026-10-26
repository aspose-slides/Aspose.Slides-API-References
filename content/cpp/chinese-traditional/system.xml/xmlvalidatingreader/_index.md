---
title: XmlValidatingReader
second_title: Aspose.Slides for C++ API 參考文件
description: 表示提供文檔類型定義（DTD）、XML-Data Reduced（XDR）結構描述以及 XML Schema 定義語言（XSD）驗證的讀取器。
type: docs
weight: 547
url: /zh-hant/system.xml/xmlvalidatingreader/
---
## XmlValidatingReader 類別


代表一個提供文件類型定義 (DTD)、XML-Data Reduced (XDR) 綱要，以及 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 驗證的閱讀器。

```cpp
class XmlValidatingReader : public System::Xml::XmlReader,
                            public System::Xml::IXmlLineInfo,
                            public System::Xml::IXmlNamespaceResolver
```

## 方法

| Method | Description |
| --- | --- |
| void [Close](./close/)() override | 將 [XmlReader::get_ReadState](../xmlreader/get_readstate/) 更改為 Closed。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 建立一個具有指定 URI 的新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 和設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、設定和解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用具有預設設定的指定串流建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的串流和設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的串流、基礎 URI 與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的串流、設定與解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文字閱讀器建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文字閱讀器與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文字閱讀器、設定與基礎 URI 建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文字閱讀器、設定與解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 閱讀器與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| void [Dispose](../xmlreader/dispose/)() override | 釋放目前 [XmlReader](../xmlreader/) 類別之實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 規範 NaN 並不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使依 IEC 60559:1989 規範 NaN 並不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 傳回目前節點上的屬性數目。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 傳回目前節點的基礎 URI。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | 傳回指示 [XmlValidatingReader](./) 是否實作二進位內容讀取方法的值。 |
| virtual **bool** [get_CanReadValueChunk](../xmlreader/get_canreadvaluechunk/)() | 傳回指示 [XmlReader](../xmlreader/) 是否實作 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 方法的值。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 傳回指示此閱讀器是否能解析與解析實體的值。 |
| **int32_t** [get_Depth](./get_depth/)() override | 傳回 XML 文件中目前節點的深度。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 傳回文件的編碼屬性。 |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | 傳回指定閱讀器如何處理實體的值。 |
| **bool** [get_EOF](./get_eof/)() override | 傳回指示閱讀器是否位於串流結尾的值。 |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | 傳回指示目前節點是否具有任何屬性的值。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 傳回指示目前節點是否可以有除 [String::Empty](../../system/string/empty/) 之外的 [XmlValidatingReader::get_Value](./get_value/) 的值。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 傳回指示目前節點是否為由文件類型定義 (DTD) 或綱要所定義之預設值產生的屬性的值。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 傳回指示目前節點是否為空元素 (例如 **<MyElement/>**) 的值。 |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | 傳回目前的行號。 |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | 傳回目前的行位置。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 傳回目前節點的本機名稱。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 傳回目前節點的限定名稱。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 傳回指示是否執行命名空間支援的值。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 傳回閱讀器所在節點的命名空間統一資源識別符 (URI)（如世界寬網路 [Web](../../system.web/) 聯盟 (W3C) 命名空間規範所定義）。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 傳回與此實作相關聯的 [XmlNameTable](../xmlnametable/)。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 傳回目前節點的類型。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 傳回與目前節點相關聯的命名空間前置詞。 |
| char16_t [get_QuoteChar](./get_quotechar/)() override | 傳回用於包住屬性節點值的引號字元。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [get_Reader](./get_reader/)() | 傳回用於建構此 [XmlValidatingReader](./) 的 [XmlReader](../xmlreader/)。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 傳回閱讀器的狀態。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | 傳回因綱要驗證而分配給目前節點的綱要資訊。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaCollection](../../system.xml.schema/xmlschemacollection/)\> [get_Schemas](./get_schemas/)() | 傳回用於驗證的 XmlSchemaCollection。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SchemaType](./get_schematype/)() | 傳回綱要類型物件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 傳回用於建立此 [XmlReader](../xmlreader/) 實例的 [XmlReaderSettings](../xmlreadersettings/) 物件。 |
| [System::Xml::ValidationType](../validationtype/) [get_ValidationType](./get_validationtype/)() | 傳回指示要執行之驗證類型的值。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 傳回目前節點的文字值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 傳回目前節點的類型。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 傳回目前的 **xml:lang** 範圍。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 傳回目前的 **xml:space** 範圍。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 傳回具有指定名稱之屬性的值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 傳回具有指定本機名稱與命名空間統一資源識別符 (URI) 的屬性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 傳回具有指定索引之屬性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類似功能。啟用自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| **bool** [HasLineInfo](./haslineinfo/)() override | 傳回指示類別是否能回傳行資訊的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 在衍生類別中覆寫時，取得具有指定索引之屬性的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](../xmlreader/get_name/) 值之屬性的值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值之屬性的值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述之型別的實例。相當於 C# 'is' 運算子。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 傳回指示字串參數是否為有效 XML 名稱的值。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 傳回指示字串參數是否為有效 XML 名稱標記的值。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/) 並測試目前內容節點是否為開始標籤或空元素標籤。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且找到的元素之 [XmlReader::get_Name](../xmlreader/get_name/) 值是否與給定的參數相符。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且找到的元素之 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否與給定字串相符。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 在目前元素的範圍內解析命名空間前置詞。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。啟用自訂型別的複製。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 移動至具有指定名稱的屬性。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 移動至具有指定本機名稱與命名空間統一資源識別符 (URI) 的屬性。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 移動至具有指定索引的屬性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 檢查目前節點是否為內容節點（非空白文字、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果節點不是內容節點，閱讀器會跳過至下一個內容節點或檔案結尾。它會略過以下類型的節點：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 移動至包含目前屬性節點的元素。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 移動至第一個屬性。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 移動至下一個屬性。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別進行複製建構。 |
| **bool** [Read](./read/)() override | 從串流讀取下一個節點。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 將屬性值解析為一個或多個 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將內容讀取為指定類型的物件。 |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取內容並傳回 Base64 解碼後的二進位位元組。 |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取內容並傳回 BinHex 解碼後的二進位位元組。 |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | 在目前位置讀取文字內容，作為 [Boolean](../../system/boolean/)。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | 在目前位置讀取文字內容，作為 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | 在目前位置讀取文字內容，作為 [DateTimeOffset](../../system/datetimeoffset/) 物件。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | 在目前位置讀取文字內容，作為 [Decimal](../../system/decimal/) 物件。 |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | 在目前位置讀取文字內容，作為雙精度浮點數。 |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | 在目前位置讀取文字內容，作為單精度浮點數。 |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | 在目前位置讀取文字內容，作為 32 位元有號整數。 |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | 在目前位置讀取文字內容，作為 64 位元有號整數。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | 在目前位置讀取文字內容，作為 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | 在目前位置讀取文字內容，作為 [String](../../system/string/) 物件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將元素內容讀取為請求的型別。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後將元素內容讀取為請求的型別。 |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取元素並解碼 Base64 內容。 |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 讀取元素並解碼 BinHex 內容。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | 讀取目前元素，並將內容作為 [Boolean](../../system/boolean/) 物件返回。 |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [Boolean](../../system/boolean/) 物件返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | 讀取目前元素，並將內容作為 [DateTime](../../system/datetime/) 物件返回。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [DateTime](../../system/datetime/) 物件返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | 讀取目前元素，並將內容作為 [Decimal](../../system/decimal/) 物件返回。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [Decimal](../../system/decimal/) 物件返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | 讀取目前元素，並將內容作為雙精度浮點數返回。 |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為雙精度浮點數返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | 讀取目前元素，並將內容作為單精度浮點數返回。 |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為單精度浮點數返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | 讀取目前元素，並將內容作為 32 位元有號整數返回。 |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 32 位元有號整數返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | 讀取目前元素，並將內容作為 64 位元有號整數返回。 |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 64 位元有號整數返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | 讀取目前元素，並將內容作為 [Object](../../system/object/) 返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [Object](../../system/object/) 返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | 讀取目前元素，並將內容作為 [String](../../system/string/) 物件返回。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本機名稱與命名空間 URI 是否與目前元素相符，然後讀取目前元素，並將內容作為 [String](../../system/string/) 物件返回。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | 讀取僅含文字的元素。但建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的處理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | 在讀取僅含文字的元素前，檢查找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否與給定字串相符。但建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的處理方式。 |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 在讀取僅含文字的元素前，檢查找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否與給定字串相符。但建議改用 [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) 方法，因為它提供更直接的處理方式。 |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | 檢查目前內容節點是否為結束標籤，並將讀取器前進至下一個節點。 |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | 在衍生類別中覆寫時，將所有內容（包括標記）讀取為字串。 |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | 在衍生類別中覆寫時，將表示此節點及其所有子節點的內容（包括標記）讀取。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | 檢查目前節點是否為元素，並將讀取器前進至下一個節點。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | 檢查目前內容節點是否為具備給定 [XmlReader::get_Name](../xmlreader/get_name/) 值的元素，並將讀取器前進至下一個節點。 |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 檢查目前內容節點是否為具備給定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的元素，並將讀取器前進至下一個節點。 |
| [String](../../system/string/) [ReadString](./readstring/)() override | 將元素或文字節點的內容讀取為字串。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | 傳回一個新的 [XmlReader](../xmlreader/) 實例，可用於讀取目前節點及其所有子孫節點。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定限定名稱的下一個子孫元素。 |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定本機名稱與命名空間 URI 的下一個子孫元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | 讀取直到找到具有指定限定名稱的元素。 |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 讀取直到找到具有指定本機名稱與命名空間 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定限定名稱的下一個同級元素。 |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](../xmlreader/) 前進至具有指定本機名稱與命名空間 URI 的下一個同級元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadTypedValue](./readtypedvalue/)() | 傳回指定 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 型別的執行期型別。 |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 讀取嵌入於 XML 文件中的大量文字資料流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 比較物件的參考。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 比較物件的參考。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以 nullptr 參考比較值型別物件。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [ResolveEntity](./resolveentity/)() override | 解析 **EntityReference** 節點的實體參考。 |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | 設定一個值，指定讀取器如何處理實體。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 設定一個值，以指示是否支援命名空間。 |
| void [set_ValidationType](./set_validationtype/)([System::Xml::ValidationType](../validationtype/)) | 設定一個值，以指示要執行的驗證類型。 |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | 設定用於解析外部文件類型定義 (DTD) 及綱要位置參考的 [XmlResolver](../xmlresolver/)。[XmlResolver](../xmlresolver/) 亦用於處理在 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 綱要中發現的任何 import 或 include 元素。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享指標）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前共享參考計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [Skip](../xmlreader/skip/)() | 略過目前節點的子節點。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | [Object.ToString()](../../system/object/tostring/) 方法在 C# 中的類似功能。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 語句的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 哨兵物件。 |
| void [ValidationEventHandler_add](./validationeventhandler_add/)(Args...) | 新增事件處理常式，以接收有關文件類型定義 (DTD)、XML-Data Reduced (XDR) 綱要，以及 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 綱要驗證錯誤的資訊。 |
| void [ValidationEventHandler_remove](./validationeventhandler_remove/)(Args...) | 移除事件處理常式，以停止接收有關文件類型定義 (DTD)、XML-Data Reduced (XDR) 綱要，以及 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 綱要驗證錯誤的資訊。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&) | 初始化一個新的 [XmlValidatingReader](./) 類別實例，以驗證從給定 [XmlReader](../xmlreader/) 回傳的內容。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 以指定的值初始化新的 [XmlValidatingReader](./) 類別實例。 |
|  [XmlValidatingReader](./xmlvalidatingreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 以指定的值初始化新的 [XmlValidatingReader](./) 類別實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |
## 備註

已棄用
:   此類別已過時。建議使用 [XmlReaderSettings](../xmlreadersettings/) 類別以及 [XmlReader::Create](../xmlreader/create/) 方法來建立驗證的 XML 讀取器。
此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標將其傳遞給函式作為參數。 

## 另請參考

* 類別 [XmlReader](../xmlreader/)
* 類別 [IXmlLineInfo](../ixmllineinfo/)
* 類別 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 命名空間 [System::Xml](../)
* 程式庫 [Aspose.Slides](../../)