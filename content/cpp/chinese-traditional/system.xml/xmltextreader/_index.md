---
title: XmlTextReader
second_title: Aspose.Slides for C++ API 參考
description: 表示一個讀取器，提供快速、非快取、僅向前的 XML 資料存取。
type: docs
weight: 508
url: /zh-hant/system.xml/xmltextreader/
---
## XmlTextReader 類別

表示一個讀取器，提供快速、非快取、僅向前的 XML 資料存取。

```cpp
class XmlTextReader : public System::Xml::XmlReader,
                      public System::Xml::IXmlLineInfo,
                      public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 說明 |
| --- | --- |
| void [Close](./close/)() override | 將 [XmlReader::get_ReadState](../xmlreader/get_readstate/) 變更為 **Closed**。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&) | 建立具有指定 URI 的新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、設定與解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的串流且採用預設設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的串流與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的串流、基礎 URI 與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的串流、設定與解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文字讀取器建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文字讀取器與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文字讀取器、設定與基礎 URI 建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文字讀取器、設定與解析的上下文資訊建立新 [XmlReader](../xmlreader/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [Create](../xmlreader/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 讀取器與設定建立新 [XmlReader](../xmlreader/) 實例。 |
| void [Dispose](../xmlreader/dispose/)() override | 釋放目前 [XmlReader](../xmlreader/) 類別實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **int32_t** [get_AttributeCount](./get_attributecount/)() override | 傳回目前節點上的屬性數量。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 傳回目前節點的基礎 URI。 |
| **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() override | 傳回一個值，指示 [XmlTextReader](./) 是否實作二進位內容讀取方法。 |
| **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() override | 傳回一個值，指示 [XmlTextReader](./) 是否實作 [XmlReader::ReadValueChunk](../xmlreader/readvaluechunk/) 方法。 |
| **bool** [get_CanResolveEntity](./get_canresolveentity/)() override | 傳回一個值，指示此讀取器是否能解析與解析實體。 |
| **int32_t** [get_Depth](./get_depth/)() override | 傳回目前節點在 XML 文件中的深度。 |
| [System::Xml::DtdProcessing](../dtdprocessing/) [get_DtdProcessing](./get_dtdprocessing/)() | 傳回 DtdProcessing 列舉。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 傳回文件的編碼。 |
| [System::Xml::EntityHandling](../entityhandling/) [get_EntityHandling](./get_entityhandling/)() | 傳回一個值，指定讀取器如何處理實體。 |
| **bool** [get_EOF](./get_eof/)() override | 傳回一個值，指示讀取器是否位於串流的末端。 |
| virtual **bool** [get_HasAttributes](../xmlreader/get_hasattributes/)() | 傳回一個值，指示目前節點是否有任何屬性。 |
| **bool** [get_HasValue](./get_hasvalue/)() override | 傳回一個值，指示目前節點是否可以有除 [String::Empty](../../system/string/empty/) 之外的 [XmlTextReader::get_Value](./get_value/)。 |
| **bool** [get_IsDefault](./get_isdefault/)() override | 傳回一個值，指示目前節點是否為從 DTD 或綱要中定義的預設值產生的屬性。 |
| **bool** [get_IsEmptyElement](./get_isemptyelement/)() override | 傳回一個值，指示目前節點是否為空元素（例如 **<MyElement/>**）。 |
| **int32_t** [get_LineNumber](./get_linenumber/)() override | 傳回目前的行號。 |
| **int32_t** [get_LinePosition](./get_lineposition/)() override | 傳回目前的行位置。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 傳回目前節點的本機名稱。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 傳回目前節點的限定名稱。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 傳回一個值，指示是否啟用命名空間支援。 |
| [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() override | 傳回讀取器所指向節點的命名空間 URI（依 W3C 命名空間規範定義）。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() override | 傳回此實作所關聯的 [XmlNameTable](../xmlnametable/)。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 傳回目前節點的類型。 |
| **bool** [get_Normalization](./get_normalization/)() | 傳回一個值，指示是否正規化空白字元與屬性值。 |
| [String](../../system/string/) [get_Prefix](./get_prefix/)() override | 傳回與目前節點相關聯的命名空間前綴。 |
| **bool** [get_ProhibitDtd](./get_prohibitdtd/)() | 傳回一個值，指示是否允許 DTD 處理。 |
| char16_t [get_QuoteChar](./get_quotechar/)() override | 傳回用於包住屬性節點值的引號字元。 |
| [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() override | 傳回讀取器的狀態。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](../xmlreader/get_schemainfo/)() | 傳回因模式驗證而指派給目前節點的模式資訊。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](../xmlreader/get_settings/)() | 傳回用來建立此 [XmlReader](../xmlreader/) 實例的 [XmlReaderSettings](../xmlreadersettings/) 物件。 |
| [String](../../system/string/) [get_Value](./get_value/)() override | 傳回目前節點的文字值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](../xmlreader/get_valuetype/)() | 傳回目前節點的類型。 |
| [System::Xml::WhitespaceHandling](../whitespacehandling/) [get_WhitespaceHandling](./get_whitespacehandling/)() | 傳回指定空白字元處理方式的值。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 傳回目前的 **xml:lang** 範圍。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 傳回目前的 **xml:space** 範圍。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) override | 傳回具有指定名稱的屬性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) override | 傳回具有指定本機名稱與命名空間 URI 的屬性值。 |
| [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) override | 傳回具有指定索引的屬性值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../xmlnamespacescope/)) override | 傳回包含目前在範圍內所有命名空間的集合。 |
| [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\> [GetRemainder](./getremainder/)() | 傳回緩衝 XML 的剩餘部分。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| **bool** [HasLineInfo](./haslineinfo/)() override | 傳回一個值，指示類別是否能傳回行資訊。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)(**int32_t**) | 在衍生類別中覆寫時，取得具有指定索引的屬性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](../xmlreader/get_name/) 值的屬性值。 |
| virtual [String](../../system/string/) [idx_get](../xmlreader/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值的屬性值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 描述的類型之實例。相當於 C# 'is' 運算子。 |
| static **bool** [IsName](../xmlreader/isname/)(const [String](../../system/string/)\&) | 傳回一個值，指示字串參數是否為有效的 XML 名稱。 |
| static **bool** [IsNameToken](../xmlreader/isnametoken/)(const [String](../../system/string/)\&) | 傳回一個值，指示字串參數是否為有效的 XML 名稱標記。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)() | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且檢查找到的元素的 [XmlReader::get_Name](../xmlreader/get_name/) 值是否與給定參數相符。 |
| virtual **bool** [IsStartElement](../xmlreader/isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](../xmlreader/movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且檢查找到的元素的 [XmlReader::get_LocalName](../xmlreader/get_localname/) 與 [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) 值是否與給定字串相符。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 在目前元素的範圍內解析命名空間前綴。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) override | 移至具有指定名稱的屬性。 |
| **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) override | 移至具有指定本機名稱與命名空間 URI 的屬性。 |
| void [MoveToAttribute](./movetoattribute/)(**int32_t**) override | 移至具有指定索引的屬性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](../xmlreader/movetocontent/)() | 檢查目前節點是否為內容節點（非空白文字、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。若節點不是內容節點，讀取器會跳過至下一個內容節點或檔案結尾。它會跳過以下類型的節點：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| **bool** [MoveToElement](./movetoelement/)() override | 移至包含目前屬性節點的元素。 |
| **bool** [MoveToFirstAttribute](./movetofirstattribute/)() override | 移至第一個屬性。 |
| **bool** [MoveToNextAttribute](./movetonextattribute/)() override | 移至下一個屬性。 |
|   [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何東西，只是初始化新物件並允許子類別的複製建構。 |
| **bool** [Read](./read/)() override | 從串流讀取下一個節點。 |
| **bool** [ReadAttributeValue](./readattributevalue/)() override | 將屬性值剖析為一個或多個 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。 |
| **int32_t** [ReadBase64](./readbase64/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 解碼 Base64 並傳回解碼後的二進位位元組。 |
| **int32_t** [ReadBinHex](./readbinhex/)(const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, **int32_t**, **int32_t**) | 解碼 **BinHex** 並傳回解碼後的二進位位元組。
| **int32_t** [ReadChars](./readchars/)(const [ArrayPtr](../../system/arrayptr/)\<char16_t\>\&, **int32_t**, **int32_t**) | Reads the text contents of an element into a character buffer. This method is designed to read large streams of embedded text by calling it successively. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](../xmlreader/readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the content as an object of the type specified. |
| **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the content and returns the **Base64** decoded binary bytes. |
| **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the content and returns the **BinHex** decoded binary bytes. |
| virtual **bool** [ReadContentAsBoolean](../xmlreader/readcontentasboolean/)() | Reads the text content at the current position as a [Boolean](../../system/boolean/). |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](../xmlreader/readcontentasdatetime/)() | Reads the text content at the current position as a [DateTime](../../system/datetime/) object. |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](../xmlreader/readcontentasdatetimeoffset/)() | Reads the text content at the current position as a [DateTimeOffset](../../system/datetimeoffset/) object. |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](../xmlreader/readcontentasdecimal/)() | Reads the text content at the current position as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadContentAsDouble](../xmlreader/readcontentasdouble/)() | Reads the text content at the current position as a double-precision floating-point number. |
| virtual **float** [ReadContentAsFloat](../xmlreader/readcontentasfloat/)() | Reads the text content at the current position as a single-precision floating point number. |
| virtual **int32_t** [ReadContentAsInt](../xmlreader/readcontentasint/)() | Reads the text content at the current position as a 32-bit signed integer. |
| virtual **int64_t** [ReadContentAsLong](../xmlreader/readcontentaslong/)() | Reads the text content at the current position as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](../xmlreader/readcontentasobject/)() | Reads the text content at the current position as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadContentAsString](../xmlreader/readcontentasstring/)() | Reads the text content at the current position as a [String](../../system/string/) object. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | Reads the element content as the requested type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](../xmlreader/readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the element content as the requested type. |
| **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the element and decodes the Base64 content. |
| **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | Reads the element and decodes the **BinHex** content. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)() | Reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual **bool** [ReadElementContentAsBoolean](../xmlreader/readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Boolean](../../system/boolean/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)() | Reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](../xmlreader/readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [DateTime](../../system/datetime/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)() | Reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](../xmlreader/readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [Decimal](../../system/decimal/) object. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)() | Reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **double** [ReadElementContentAsDouble](../xmlreader/readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a double-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)() | Reads the current element and returns the contents as single-precision floating-point number. |
| virtual **float** [ReadElementContentAsFloat](../xmlreader/readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a single-precision floating-point number. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)() | Reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int32_t** [ReadElementContentAsInt](../xmlreader/readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 32-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)() | Reads the current element and returns the contents as a 64-bit signed integer. |
| virtual **int64_t** [ReadElementContentAsLong](../xmlreader/readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a 64-bit signed integer. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)() | Reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](../xmlreader/readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as an [Object](../../system/object/). |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)() | Reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementContentAsString](../xmlreader/readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the specified local name and namespace URI matches that of the current element, then reads the current element and returns the contents as a [String](../../system/string/) object. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)() | Reads a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/)) | Checks that the [XmlReader::get_Name](../xmlreader/get_name/) value of the element found matches the given string before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual [String](../../system/string/) [ReadElementString](../xmlreader/readelementstring/)([String](../../system/string/), [String](../../system/string/)) | Checks that the [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values of the element found matches the given strings before reading a text-only element. However, it is recommended to use the [XmlReader::ReadElementContentAsString](../xmlreader/readelementcontentasstring/) method instead, because it provides a more straightforward way to handle this operation. |
| virtual void [ReadEndElement](../xmlreader/readendelement/)() | Checks that the current content node is an end tag and advances the reader to the next node. |
| virtual [String](../../system/string/) [ReadInnerXml](../xmlreader/readinnerxml/)() | When overridden in a derived class, reads all the content, including markup, as a string. |
| virtual [String](../../system/string/) [ReadOuterXml](../xmlreader/readouterxml/)() | When overridden in a derived class, reads the content, including markup, representing this node and all its children. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)() | Checks that the current node is an element and advances the reader to the next node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_Name](../xmlreader/get_name/) value and advances the reader to the next node. |
| virtual void [ReadStartElement](../xmlreader/readstartelement/)([String](../../system/string/), [String](../../system/string/)) | Checks that the current content node is an element with the given [XmlReader::get_LocalName](../xmlreader/get_localname/) and [XmlReader::get_NamespaceURI](../xmlreader/get_namespaceuri/) values and advances the reader to the next node. |
| [String](../../system/string/) [ReadString](./readstring/)() override | Reads the contents of an element or a text node as a string. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\> [ReadSubtree](../xmlreader/readsubtree/)() | Returns a new [XmlReader](../xmlreader/) instance that can be used to read the current node, and all its descendants. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next descendant element with the specified qualified name. |
| virtual **bool** [ReadToDescendant](../xmlreader/readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next descendant element with the specified local name and namespace URI. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/)) | Reads until an element with the specified qualified name is found. |
| virtual **bool** [ReadToFollowing](../xmlreader/readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | Reads until an element with the specified local name and namespace URI is found. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next sibling element with the specified qualified name. |
| virtual **bool** [ReadToNextSibling](../xmlreader/readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | Advances the [XmlReader](../xmlreader/) to the next sibling element with the specified local name and namespace URI. |
| virtual **int32_t** [ReadValueChunk](../xmlreader/readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | Reads large streams of text embedded in an XML document. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [ResetState](./resetstate/)() | Resets the state of the reader to [ReadState::Initial](../readstate/). |
| void [ResolveEntity](./resolveentity/)() override | Resolves the entity reference for **EntityReference** nodes. |
| void [set_DtdProcessing](./set_dtdprocessing/)([System::Xml::DtdProcessing](../dtdprocessing/)) | Sets the DtdProcessing enumeration. |
| void [set_EntityHandling](./set_entityhandling/)([System::Xml::EntityHandling](../entityhandling/)) | Sets a value that specifies how the reader handles entities. |
| void [set_Namespaces](./set_namespaces/)(**bool**) | Sets a value indicating whether to do namespace support. |
| void [set_Normalization](./set_normalization/)(**bool**) | Sets a value indicating whether to normalize white space and attribute values. |
| void [set_ProhibitDtd](./set_prohibitdtd/)(**bool**) | Sets a value indicating whether to allow DTD processing. |
| void [set_WhitespaceHandling](./set_whitespacehandling/)([System::Xml::WhitespaceHandling](../whitespacehandling/)) | Sets a value that specifies how white space is handled. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>\&) | Sets the [XmlResolver](../xmlresolver/) used for resolving DTD references. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [Skip](./skip/)() override | Skips the children of the current node. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified stream. |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL and stream. |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified stream and [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | Initializes a new instance of the [XmlTextReader](./) class with the specified URL, stream and [XmlNameTable](../xmlnametable/). |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的 TextReader 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的 URL 和 TextReader 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 TextReader 和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 URL、TextReader 和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 stream、XmlNodeType 和 [XmlParserContext](../xmlparsercontext/) 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, [XmlNodeType](../xmlnodetype/), const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 string、XmlNodeType 和 [XmlParserContext](../xmlparsercontext/) 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&) | 使用指定的 file 初始化 [XmlTextReader](./) 類別的新執行個體。 |
|  [XmlTextReader](./xmltextreader/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 file 和 [XmlNameTable](../xmlnametable/) 初始化 [XmlTextReader](./) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |
## 型別別名

| 別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的 shared pointer 別名。 |
## 備註

建議改用 [XmlReader](../xmlreader/) 類別。

此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式進行配置。絕不要在堆疊上或使用 operator new 建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 另請參閱

* 類別 [XmlReader](../xmlreader/)
* 類別 [IXmlLineInfo](../ixmllineinfo/)
* 類別 [IXmlNamespaceResolver](../ixmlnamespaceresolver/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)