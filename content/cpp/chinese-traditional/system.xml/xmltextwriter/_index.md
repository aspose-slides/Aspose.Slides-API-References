---
title: XmlTextWriter
second_title: Aspose.Slides for C++ API 參考
description: 表示一個寫入器，提供快速、非快取、僅向前的方式來產生符合 W3C 可擴充標記語言 (XML) 1.0 以及 XML 命名空間建議的串流或檔案。
type: docs
weight: 521
url: /zh-hant/system.xml/xmltextwriter/
---
## XmlTextWriter 類別

表示一個寫入器，提供快速、非快取、僅向前的方式來產生符合 W3C 可擴充標記語言 (XML) 1.0 以及 XML 命名空間建議的串流或檔案。

```cpp
class XmlTextWriter : public System::Xml::XmlWriter
```

## 方法

| 方法 | 描述 |
| --- | --- |
| void [Close](./close/)() override | 關閉此串流以及底層串流。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&) | 使用指定的檔名建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用檔名和 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的串流建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用串流和 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 TextWriter 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 [Text::StringBuilder](../../system.text/stringbuilder/) 建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 [Text::StringBuilder](../../system.text/stringbuilder/) 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) | 使用指定的 [XmlWriter](../xmlwriter/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\> [Create](../xmlwriter/create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用指定的 [XmlWriter](../xmlwriter/) 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](../xmlwriter/) 實例。 |
| void [Dispose](../xmlwriter/dispose/)() override | 釋放目前 [XmlWriter](../xmlwriter/) 類別實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| void [Flush](./flush/)() override | 將緩衝區中的資料寫入底層串流，並同時刷新底層串流。 |
| [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\> [get_BaseStream](./get_basestream/)() | 傳回底層串流物件。 |
| [System::Xml::Formatting](../formatting/) [get_Formatting](./get_formatting/)() | 指示輸出如何格式化。 |
| **int32_t** [get_Indentation](./get_indentation/)() | 當 [XmlTextWriter::set_Formatting](./set_formatting/) 設為 [Formatting::Indented](../formatting/) 時，傳回在階層每個層級要寫入多少個 IndentChars。 |
| char16_t [get_IndentChar](./get_indentchar/)() | 當 [XmlTextWriter::set_Formatting](./set_formatting/) 設為 [Formatting::Indented](../formatting/) 時，傳回用於縮排的字元。 |
| **bool** [get_Namespaces](./get_namespaces/)() | 傳回指示是否啟用命名空間支援的值。 |
| char16_t [get_QuoteChar](./get_quotechar/)() | 傳回用於引用屬性值的字元。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](../xmlwriter/get_settings/)() | 傳回用於建立此 [XmlWriter](../xmlwriter/) 實例的 [XmlWriterSettings](../xmlwritersettings/) 物件。 |
| [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() override | 傳回寫入器的狀態。 |
| [String](../../system/string/) [get_XmlLang](./get_xmllang/)() override | 傳回目前的 **xml:lang** 範圍。 |
| [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() override | 傳回表示目前 **xml:space** 範圍的 XmlSpace。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述的類型實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) override | 傳回在目前命名空間範圍內對於該命名空間 URI 定義的最接近前置詞。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂類型的複製。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 拷貝建構函式。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會拷貝任何內容，只是初始化新物件，並允許子類別的拷貝建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化，針對字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的值。 |
| void [set_Formatting](./set_formatting/)([System::Xml::Formatting](../formatting/)) | 指示輸出如何格式化。 |
| void [set_Indentation](./set_indentation/)(**int32_t**) | 當 [XmlTextWriter::set_Formatting](./set_formatting/) 設為 [Formatting::Indented](../formatting/) 時，設定在階層每個層級要寫入多少個 IndentChars。 |
| void [set_IndentChar](./set_indentchar/)(char16_t) | 當 [XmlTextWriter::set_Formatting](./set_formatting/) 設為 [Formatting::Indented](../formatting/) 時，設定用於縮排的字元。 |
| void [set_Namespaces](./set_namespaces/)(**bool**) | 設定指示是否啟用命名空間支援的值。 |
| void [set_QuoteChar](./set_quotechar/)(char16_t) | 設定用於引用屬性值的字元。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享），允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。啟用將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫，請改用智慧指標或 ThisProtector。 |
| virtual void [WriteAttributes](../xmlwriter/writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在衍生類別中覆寫時，寫出 [XmlReader](../xmlreader/) 目前位置所找到的所有屬性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在衍生類別中覆寫時，寫出具有指定本地名稱、命名空間 URI 與值的屬性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在衍生類別中覆寫時，寫出具有指定本地名稱與值的屬性。 |
| void [WriteAttributeString](../xmlwriter/writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在衍生類別中覆寫時，寫出具有指定前置詞、本地名稱、命名空間 URI 與值的屬性。 |
| void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 將指定的二進位位元組編碼為 base64，並寫出產生的文字。 |
| void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) override | 將指定的二進位位元組編碼為 binhex，並寫出產生的文字。 |
| void [WriteCData](./writecdata/)([String](../../system/string/)) override | 寫出包含指定文字的 **...** 區塊。 |
| void [WriteCharEntity](./writecharentity/)(char16_t) override | 強制產生指定 Unicode 字元值的字元實體。 |
| void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 一次寫入一個緩衝區的文字。 |
| void [WriteComment](./writecomment/)([String](../../system/string/)) override | 寫出包含指定文字的註解 ****。 |
| void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 寫出具有指定名稱與可選屬性的 DOCTYPE 宣告。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫出具有指定本地名稱與值的元素。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫出具有指定本地名稱、命名空間 URI 與值的元素。 |
| void [WriteElementString](../xmlwriter/writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫出具有指定前置詞、本地名稱、命名空間 URI 與值的元素。 |
| void [WriteEndAttribute](./writeendattribute/)() override | 關閉先前的 [XmlTextWriter::WriteStartAttribute](./writestartattribute/) 呼叫。 |
| void [WriteEndDocument](./writeenddocument/)() override | 關閉任何開啟的元素或屬性，並將寫入器重新置於起始狀態。 |
| void [WriteEndElement](./writeendelement/)() override | 關閉一個元素並彈出相對應的命名空間範圍。 |
| void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) override | 寫出形式為 **&name**; 的實體參照。 |
| void [WriteFullEndElement](./writefullendelement/)() override | 關閉一個元素並彈出相對應的命名空間範圍。 |
| void [WriteName](./writename/)(const [String](../../system/string/)\&) override | 寫出指定的名稱，並確保其符合 [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) 的有效名稱規則。 |
| void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) override | 寫出指定的名稱，並確保其符合 [W3C XML 1.0 recommendation](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name) 所定的有效 **NmToken**。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 在衍生類別中覆寫時，將讀取器的所有內容複製到寫入器，並將讀取器移至下一個兄弟節點的開始位置。 |
| virtual void [WriteNode](../xmlwriter/writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | 將 XPathNavigator 物件的所有內容複製到寫入器。XPathNavigator 的位置保持不變。 |
| void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) override | 寫出一個處理指令，其名稱與文字之間有空格，如 **<?name text?>**。 |
| void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 寫出具命名空間限定的名稱。此方法會查找該命名空間範圍內的前置詞。 |
| void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) override | 從字元緩衝區手動寫入原始標記。 |
| void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) override | 從字串手動寫入原始標記。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 寫出屬性的開始。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫出具有指定本地名稱與命名空間 URI 的屬性開始。 |
| void [WriteStartAttribute](../xmlwriter/writestartattribute/)(const [String](../../system/string/)\&) | 寫出具有指定本地名稱的屬性開始。 |
| void [WriteStartDocument](./writestartdocument/)() override | 寫出版本為 "1.0" 的 XML 宣告。 |
| void [WriteStartDocument](./writestartdocument/)(**bool**) override | 寫出版本為 "1.0" 且含 standalone 屬性的 XML 宣告。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) override | 寫出指定的起始標籤，並將其與給定的命名空間與前置詞關聯。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 在衍生類別中覆寫時，寫出指定的起始標籤，並將其與給定的命名空間關聯。 |
| void [WriteStartElement](../xmlwriter/writestartelement/)(const [String](../../system/string/)\&) | 在衍生類別中覆寫時，寫出具有指定本地名稱的起始標籤。 |
| void [WriteString](./writestring/)(const [String](../../system/string/)\&) override | 寫出給定的文字內容。 |
| void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) override | 產生並寫出代理字元對的代理字元實體。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 寫出物件的值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(const [String](../../system/string/)\&) | 寫出一個 [String](../../system/string/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**bool**) | 寫出一個 [Boolean](../../system/boolean/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTime](../../system/datetime/)) | 寫出一個 [DateTime](../../system/datetime/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | 寫出一個 [DateTimeOffset](../../system/datetimeoffset/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**double**) | 寫出一個 [Double](../../system/double/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**float**) | 寫出單精度浮點數。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)([Decimal](../../system/decimal/)) | 寫出一個 [Decimal](../../system/decimal/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int32_t**) | 寫出一個 [Int32](../../system/int32/) 值。 |
| virtual void [WriteValue](../xmlwriter/writevalue/)(**int64_t**) | 寫出一個 [Int64](../../system/int64/) 值。 |
| void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) override |寫出給定的空白字元。 |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 使用指定的串流與編碼建立 [XmlTextWriter](./) 類別的實例。 |
|  [XmlTextWriter](./xmltextwriter/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\>\&) | 使用指定的檔案建立 [XmlTextWriter](./) 類別的實例。 |
|  [XmlTextWriter](./xmltextwriter/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 建立 [XmlTextWriter](./) 類別的實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 類型定義

| 類型別名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 備註

建議改用 [XmlWriter](../xmlwriter/) 類別。

此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。切勿在堆疊上或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤或斷言失敗。應始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 另請參閱

* 類別 [XmlWriter](../xmlwriter/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)