---
title: XmlReader
second_title: Aspose.Slides for C++ API 參考手冊
description: 表示一個讀取器，提供快速、非快取、僅向前的 XML 資料存取。
type: docs
weight: 430
url: /zh-hant/system.xml/xmlreader/
---
## XmlReader 類別


Represents a reader that provides fast, noncached, forward-only access to XML data.

```cpp
class XmlReader : public System::IDisposable
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual void [Close](./close/)() | 當在衍生類別中覆寫時，將 [XmlReader::get_ReadState](./get_readstate/) 變更為 [ReadState::Closed](../readstate/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 建立具有指定 URI 的新 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的 URI 和設定建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的 URI、設定和解析的上下文資訊建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的串流與預設設定建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的串流與設定建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的串流、基礎 URI 與設定建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的串流、設定以及解析的上下文資訊建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&) | 使用指定的文字讀取器建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>\&) | 使用指定的文字讀取器與設定建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [String](../../system/string/)\&) | 使用指定的文字讀取器、設定與基礎 URI 建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>, const [SharedPtr](../../system/sharedptr/)\<[XmlParserContext](../xmlparsercontext/)\>\&) | 使用指定的文字讀取器、設定與解析的上下文資訊建立新的 [XmlReader](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\>) | 使用指定的 XML 讀取器與設定建立新的 [XmlReader](./) 實例。 |
| void [Dispose](./dispose/)() override | 釋放 [XmlReader](./) 類別之目前實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 使用 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，將兩個 NaN 視為相等，即使依據 IEC 60559:1989 NaN 與任何值（包括 NaN）皆不相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual **int32_t** [get_AttributeCount](./get_attributecount/)() | 當在衍生類別中覆寫時，取得目前節點的屬性數量。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 當在衍生類別中覆寫時，取得目前節點的基礎 URI。 |
| virtual **bool** [get_CanReadBinaryContent](./get_canreadbinarycontent/)() | 傳回一個值，指示 [XmlReader](./) 是否實作二進位內容讀取方法。 |
| virtual **bool** [get_CanReadValueChunk](./get_canreadvaluechunk/)() | 傳回一個值，指示 [XmlReader](./) 是否實作 [XmlReader::ReadValueChunk](./readvaluechunk/) 方法。 |
| virtual **bool** [get_CanResolveEntity](./get_canresolveentity/)() | 傳回一個值，指示此讀取器是否能解析與解析實體。 |
| virtual **int32_t** [get_Depth](./get_depth/)() | 當在衍生類別中覆寫時，取得 XML 文件中目前節點的深度。 |
| virtual **bool** [get_EOF](./get_eof/)() | 當在衍生類別中覆寫時，取得一個值，指示讀取器是否位於串流的結尾。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 傳回一個值，指示目前節點是否擁有任何屬性。 |
| virtual **bool** [get_HasValue](./get_hasvalue/)() | 當在衍生類別中覆寫時，取得一個值，指示目前節點是否可以具有 [XmlReader::get_Value](./get_value/) 值。 |
| virtual **bool** [get_IsDefault](./get_isdefault/)() | 當在衍生類別中覆寫時，取得一個值，指示目前節點是否為由 DTD 或綱要中定義的預設值產生的屬性。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 當在衍生類別中覆寫時，取得一個值，指示目前節點是否為空元素（例如 **<MyElement/>**）。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 當在衍生類別中覆寫時，取得目前節點的本地名稱。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 當在衍生類別中覆寫時，取得目前節點的限定名稱。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 當在衍生類別中覆寫時，取得讀取器所在節點的命名空間 URI（依 W3C 命名空間規範定義）。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 當在衍生類別中覆寫時，取得與此實作相關的 [XmlNameTable](../xmlnametable/)。 |
| virtual [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() | 當在衍生類別中覆寫時，取得目前節點的類型。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 當在衍生類別中覆寫時，取得與目前節點相關的命名空間前綴。 |
| virtual char16_t [get_QuoteChar](./get_quotechar/)() | 當在衍生類別中覆寫時，取得用於包圍屬性節點值的引號字元。 |
| virtual [System::Xml::ReadState](../readstate/) [get_ReadState](./get_readstate/)() | 當在衍生類別中覆寫時，取得讀取器的狀態。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 傳回因模式驗證而指派給目前節點的模式資訊。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReaderSettings](../xmlreadersettings/)\> [get_Settings](./get_settings/)() | 傳回用於建立此 [XmlReader](./) 實例的 [XmlReaderSettings](../xmlreadersettings/) 物件。 |
| virtual [String](../../system/string/) [get_Value](./get_value/)() | 當在衍生類別中覆寫時，取得目前節點的文字值。 |
| virtual [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() | 傳回目前節點的類型。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 當在衍生類別中覆寫時，取得目前的 **xml:lang** 範圍。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 當在衍生類別中覆寫時，取得目前的 **xml:space** 範圍。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/)) | 當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](./get_name/) 值之屬性的值。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值之屬性的值。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)(**int32_t**) | 當在衍生類別中覆寫時，取得指定索引之屬性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) | 當在衍生類別中覆寫時，取得指定索引之屬性的值。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | 當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_Name](./get_name/) 值之屬性的值。 |
| virtual [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/), [String](../../system/string/)) | 當在衍生類別中覆寫時，取得具有指定 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值之屬性的值。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表由 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| static **bool** [IsName](./isname/)(const [String](../../system/string/)\&) | 傳回一個值，指示字串參數是否為有效的 XML 名稱。 |
| static **bool** [IsNameToken](./isnametoken/)(const [String](../../system/string/)\&) | 傳回一個值，指示字串參數是否為有效的 XML 名稱標記。 |
| virtual **bool** [IsStartElement](./isstartelement/)() | 呼叫 [XmlReader::MoveToContent](./movetocontent/) 並測試目前內容節點是否為開始標籤或空元素標籤。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](./movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且檢查找到的元素的 [XmlReader::get_Name](./get_name/) 值是否與給定參數相符。 |
| virtual **bool** [IsStartElement](./isstartelement/)([String](../../system/string/), [String](../../system/string/)) | 呼叫 [XmlReader::MoveToContent](./movetocontent/)，測試目前內容節點是否為開始標籤或空元素標籤，且檢查找到的元素的 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值是否與給定字串相符。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) | 當在衍生類別中覆寫時，解析目前元素範圍內的命名空間前綴。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/)) | 當在衍生類別中覆寫時，移動至具有指定 [XmlReader::get_Name](./get_name/) 值的屬性。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | 當在衍生類別中覆寫時，移動至具有指定 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的屬性。 |
| virtual void [MoveToAttribute](./movetoattribute/)(**int32_t**) | 當在衍生類別中覆寫時，移動至具有指定索引的屬性。 |
| virtual [XmlNodeType](../xmlnodetype/) [MoveToContent](./movetocontent/)() | 檢查目前節點是否為內容節點（非空白文字、**CDATA**、**Element**、**EndElement**、**EntityReference** 或 **EndEntity**）。如果節點不是內容節點，讀取器會跳過至下一個內容節點或檔案結尾。它會略過以下類型的節點：**ProcessingInstruction**、**DocumentType**、**Comment**、**Whitespace** 或 **SignificantWhitespace**。 |
| virtual **bool** [MoveToElement](./movetoelement/)() | 當在衍生類別中覆寫時，移動至包含目前屬性節點的元素。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 當在衍生類別中覆寫時，移動至第一個屬性。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 當在衍生類別中覆寫時，移動至下一個屬性。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| virtual **bool** [Read](./read/)() | 當在衍生類別中覆寫時，從串流讀取下一個節點。 |
| virtual **bool** [ReadAttributeValue](./readattributevalue/)() | 當在衍生類別中覆寫時，將屬性值解析為一個或多個 **[Text](../../system.text/)**、**EntityReference** 或 **EndEntity** 節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAs](./readcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將內容讀取為指定類型的物件。 |
| virtual **int32_t** [ReadContentAsBase64](./readcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 讀取內容並傳回 Base64 解碼後的二進位位元組。 |
| virtual **int32_t** [ReadContentAsBinHex](./readcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 讀取內容並傳回 **BinHex** 解碼後的二進位位元組。 |
| virtual **bool** [ReadContentAsBoolean](./readcontentasboolean/)() | 將目前位置的文字內容讀取為 [Boolean](../../system/boolean/)。 |
| virtual [DateTime](../../system/datetime/) [ReadContentAsDateTime](./readcontentasdatetime/)() | 讀取目前位置的文字內容，作為 [DateTime](../../system/datetime/) 物件。 |
| virtual [DateTimeOffset](../../system/datetimeoffset/) [ReadContentAsDateTimeOffset](./readcontentasdatetimeoffset/)() | 讀取目前位置的文字內容，作為 [DateTimeOffset](../../system/datetimeoffset/) 物件。 |
| virtual [Decimal](../../system/decimal/) [ReadContentAsDecimal](./readcontentasdecimal/)() | 讀取目前位置的文字內容，作為 [Decimal](../../system/decimal/) 物件。 |
| virtual **double** [ReadContentAsDouble](./readcontentasdouble/)() | 讀取目前位置的文字內容，作為雙精度浮點數。 |
| virtual **float** [ReadContentAsFloat](./readcontentasfloat/)() | 讀取目前位置的文字內容，作為單精度浮點數。 |
| virtual **int32_t** [ReadContentAsInt](./readcontentasint/)() | 讀取目前位置的文字內容，作為 32 位元有號整數。 |
| virtual **int64_t** [ReadContentAsLong](./readcontentaslong/)() | 讀取目前位置的文字內容，作為 64 位元有號整數。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadContentAsObject](./readcontentasobject/)() | 讀取目前位置的文字內容，作為一個 [Object](../../system/object/)。 |
| virtual [String](../../system/string/) [ReadContentAsString](./readcontentasstring/)() | 讀取目前位置的文字內容，作為 [String](../../system/string/) 物件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>) | 將元素內容讀取為所請求的型別。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAs](./readelementcontentas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../ixmlnamespaceresolver/)\>, [String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後將元素內容讀取為所請求的型別。 |
| virtual **int32_t** [ReadElementContentAsBase64](./readelementcontentasbase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 讀取元素並解碼 **Base64** 內容。 |
| virtual **int32_t** [ReadElementContentAsBinHex](./readelementcontentasbinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 讀取元素並解碼 **BinHex** 內容。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)() | 讀取目前元素，並以 [Boolean](../../system/boolean/) 物件返回其內容。 |
| virtual **bool** [ReadElementContentAsBoolean](./readelementcontentasboolean/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素並以 [Boolean](../../system/boolean/) 物件返回其內容。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)() | 讀取目前元素，並以 [DateTime](../../system/datetime/) 物件返回其內容。 |
| virtual [DateTime](../../system/datetime/) [ReadElementContentAsDateTime](./readelementcontentasdatetime/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素並以 [DateTime](../../system/datetime/) 物件返回其內容。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)() | 讀取目前元素，並以 [Decimal](../../system/decimal/) 物件返回其內容。 |
| virtual [Decimal](../../system/decimal/) [ReadElementContentAsDecimal](./readelementcontentasdecimal/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素並以 [Decimal](../../system/decimal/) 物件返回其內容。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)() | 讀取目前元素，並以雙精度浮點數返回其內容。 |
| virtual **double** [ReadElementContentAsDouble](./readelementcontentasdouble/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以雙精度浮點數返回其內容。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)() | 讀取目前元素，並以單精度浮點數返回其內容。 |
| virtual **float** [ReadElementContentAsFloat](./readelementcontentasfloat/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以單精度浮點數返回其內容。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)() | 讀取目前元素，並以 32 位元有號整數返回其內容。 |
| virtual **int32_t** [ReadElementContentAsInt](./readelementcontentasint/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以 32 位元有號整數返回其內容。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)() | 讀取目前元素，並以 64 位元有號整數返回其內容。 |
| virtual **int64_t** [ReadElementContentAsLong](./readelementcontentaslong/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以 64 位元有號整數返回其內容。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)() | 讀取目前元素，並以 [Object](../../system/object/) 物件返回其內容。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ReadElementContentAsObject](./readelementcontentasobject/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以 [Object](../../system/object/) 物件返回其內容。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)() | 讀取目前元素，並以 [String](../../system/string/) 物件返回其內容。 |
| virtual [String](../../system/string/) [ReadElementContentAsString](./readelementcontentasstring/)([String](../../system/string/), [String](../../system/string/)) | 檢查指定的本地名稱和命名空間 URI 是否與目前元素相符，然後讀取目前元素，並以 [String](../../system/string/) 物件返回其內容。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)() | 讀取僅文字元素。不過，建議改用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/)) | 在讀取僅文字元素前，檢查找到的元素之 [XmlReader::get_Name](./get_name/) 值是否與給定字串相符。不過，建議改用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual [String](../../system/string/) [ReadElementString](./readelementstring/)([String](../../system/string/), [String](../../system/string/)) | 在讀取僅文字元素前，檢查找到的元素之 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值是否與給定字串相符。不過，建議改用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual void [ReadEndElement](./readendelement/)() | 檢查目前內容節點是否為結束標籤，並將閱讀器前進至下一個節點。 |
| virtual [String](../../system/string/) [ReadInnerXml](./readinnerxml/)() | 在衍生類別中覆寫時，將所有內容（含標記）讀取為字串。 |
| virtual [String](../../system/string/) [ReadOuterXml](./readouterxml/)() | 在衍生類別中覆寫時，讀取代表此節點及其所有子節點的內容（含標記）。 |
| virtual void [ReadStartElement](./readstartelement/)() | 檢查目前節點是否為元素，並將閱讀器前進至下一個節點。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/)) | 檢查目前內容節點是否為具有給定 [XmlReader::get_Name](./get_name/) 值的元素，並將閱讀器前進至下一個節點。 |
| virtual void [ReadStartElement](./readstartelement/)([String](../../system/string/), [String](../../system/string/)) | 檢查目前內容節點是否為具有給定 [XmlReader::get_LocalName](./get_localname/) 與 [XmlReader::get_NamespaceURI](./get_namespaceuri/) 值的元素，並將閱讀器前進至下一個節點。 |
| virtual [String](../../system/string/) [ReadString](./readstring/)() | 在衍生類別中覆寫時，將元素或文字節點的內容讀取為字串。不過，建議改用 [XmlReader::ReadElementContentAsString](./readelementcontentasstring/) 方法，因為它提供更直接的操作方式。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](./)\> [ReadSubtree](./readsubtree/)() | 傳回一個新的 [XmlReader](./) 實例，可用於讀取目前節點及其所有子孫節點。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/)) | 將 [XmlReader](./) 前進至具有指定限定名稱的下一個子孫元素。 |
| virtual **bool** [ReadToDescendant](./readtodescendant/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](./) 前進至具有指定本地名稱與命名空間 URI 的下一個子孫元素。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/)) | 讀取直至找到具有指定限定名稱的元素。 |
| virtual **bool** [ReadToFollowing](./readtofollowing/)([String](../../system/string/), [String](../../system/string/)) | 讀取直至找到具有指定本地名稱與命名空間 URI 的元素。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/)) | 將 [XmlReader](./) 前進至具有指定限定名稱的下一個同級元素。 |
| virtual **bool** [ReadToNextSibling](./readtonextsibling/)([String](../../system/string/), [String](../../system/string/)) | 將 [XmlReader](./) 前進至具有指定本地名稱與命名空間 URI 的下一個同級元素。 |
| virtual **int32_t** [ReadValueChunk](./readvaluechunk/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 讀取嵌入於 XML 文件中的大型文字串流。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，適用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| virtual void [ResolveEntity](./resolveentity/)() | 在衍生類別中覆寫時，解析 **EntityReference** 節點的實體參考。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並返回共享參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [Skip](./skip/)() | 跳過目前節點的子節點。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不要直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 類型別名

| 類型別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 參見

* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)