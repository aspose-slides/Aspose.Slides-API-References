---
title: XmlWriter
second_title: Aspose.Slides C++ API 參考
description: 表示一種寫入器，提供快速、非快取、僅向前的方式來產生包含 XML 資料的串流或檔案。
type: docs
weight: 573
url: /zh-hant/system.xml/xmlwriter/
---
## XmlWriter 類別


Represents a writer that provides a fast, non-cached, forward-only way to generate streams or files that contain XML data.

```cpp
class XmlWriter : public System::IDisposable
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual void [Close](./close/)() | 當在衍生類別中被覆寫時，關閉此串流以及基礎串流。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&) | 使用指定的檔案名稱建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [String](../../system/string/)\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用檔案名稱和 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | 使用指定的串流建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用串流與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | 使用指定的 TextWriter 建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 TextWriter 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | 使用指定的 [Text::StringBuilder](../../system.text/stringbuilder/) 建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用 [Text::StringBuilder](../../system.text/stringbuilder/) 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&) | 使用指定的 [XmlWriter](./) 物件建立新的 [XmlWriter](./) 實例。 |
| static [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\> [Create](./create/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](./)\>\&, [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\>) | 使用指定的 [XmlWriter](./) 與 [XmlWriterSettings](../xmlwritersettings/) 物件建立新的 [XmlWriter](./) 實例。 |
| void [Dispose](./dispose/)() override | 釋放 [XmlWriter](./) 類別當前實例所使用的所有資源。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考類型物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值類型物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，即使根據 IEC 60559:1989 兩個 NaN 不相等，也視為相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，即使根據 IEC 60559:1989 兩個 NaN 不相等，也視為相等。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual void [Flush](./flush/)() | 當在衍生類別中被覆寫時，將緩衝區內容刷新至基礎串流，並同時刷新基礎串流。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](../xmlwritersettings/)\> [get_Settings](./get_settings/)() | 回傳用於建立此 [XmlWriter](./) 實例的 [XmlWriterSettings](../xmlwritersettings/) 物件。 |
| virtual [System::Xml::WriteState](../writestate/) [get_WriteState](./get_writestate/)() | 當在衍生類別中被覆寫時，取得寫入器的狀態。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 當在衍生類別中被覆寫時，取得目前的 **xml:lang** 範圍。 |
| virtual [System::Xml::XmlSpace](../xmlspace/) [get_XmlSpace](./get_xmlspace/)() | 當在衍生類別中被覆寫時，取得代表目前 **xml:space** 範圍的 XmlSpace。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法的類比。允許自訂物件的雜湊。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際型別。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為目標類型的實例。相當於 C# 的 `is` 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# `lock()` 陳述式的鎖定機制。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [String](../../system/string/) [LookupPrefix](./lookupprefix/)([String](../../system/string/)) | 當在衍生類別中被覆寫時，回傳目前命名空間範圍中對應於命名空間 URI 的最近前綴。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法的類比。允許自訂型別的克隆。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式比較值型別物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | `[Object::ReferenceEquals](../../system/object/referenceequals/)` 的特化，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | `[Object::ReferenceEquals](../../system/object/referenceequals/)` 的特化，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 依指定值遞減共享參考計數。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 設定第 n 個模板參數為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得當前共享參考計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 增加共享參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 減少並回傳共享參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) 方法的類比。允許將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# `typeof([System.Object](../../system/object/))` 造型。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# `lock()` 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 增加弱參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 減少弱參考計數。不要直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual void [WriteAttributes](./writeattributes/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 當在衍生類別中被覆寫時，寫入目前位置在 [XmlReader](../xmlreader/) 中找到的所有屬性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定本地名稱、命名空間 URI 與值的屬性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定本地名稱與值的屬性。 |
| void [WriteAttributeString](./writeattributestring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定前綴、本地名稱、命名空間 URI 與值的屬性。 |
| virtual void [WriteBase64](./writebase64/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 當在衍生類別中被覆寫時，將指定的二進位位元組以 Base64 編碼並寫入產生的文字。 |
| virtual void [WriteBinHex](./writebinhex/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | 當在衍生類別中被覆寫時，將指定的二進位位元組以 **BinHex** 編碼並寫入產生的文字。 |
| virtual void [WriteCData](./writecdata/)([String](../../system/string/)) | 當在衍生類別中被覆寫時，寫入包含指定文字的 **...** 區塊。 |
| virtual void [WriteCharEntity](./writecharentity/)(char16_t) | 當在衍生類別中被覆寫時，強制產生指定 Unicode 字元值的字符實體。 |
| virtual void [WriteChars](./writechars/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 當在衍生類別中被覆寫時，以緩衝區為單位寫入文字。 |
| virtual void [WriteComment](./writecomment/)([String](../../system/string/)) | 當在衍生類別中被覆寫時，寫入包含指定文字的 ******** 註解。 |
| virtual void [WriteDocType](./writedoctype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定名稱與可選屬性的 DOCTYPE 宣告。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫入具有指定本地名稱與值的元素。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫入具有指定本地名稱、命名空間 URI 與值的元素。 |
| void [WriteElementString](./writeelementstring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫入具有指定前綴、本地名稱、命名空間 URI 與值的元素。 |
| virtual void [WriteEndAttribute](./writeendattribute/)() | 當在衍生類別中被覆寫時，關閉先前的 XmlWriter::WriteStartAttribute(String,String) 呼叫。 |
| virtual void [WriteEndDocument](./writeenddocument/)() | 當在衍生類別中被覆寫時，關閉所有開啟的元素或屬性，並將寫入器恢復至 Start 狀態。 |
| virtual void [WriteEndElement](./writeendelement/)() | 當在衍生類別中被覆寫時，關閉一個元素並彈出相應的命名空間範圍。 |
| virtual void [WriteEntityRef](./writeentityref/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，以 **&name**; 形式寫入實體參考。 |
| virtual void [WriteFullEndElement](./writefullendelement/)() | 當在衍生類別中被覆寫時，關閉一個元素並彈出相應的命名空間範圍。 |
| virtual void [WriteName](./writename/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入指定名稱，並確保其符合 W3C XML 1.0 推薦規範的有效名稱 ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name))。 |
| virtual void [WriteNmToken](./writenmtoken/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入指定名稱，並確保其符合 W3C XML 1.0 推薦規範的有效 NmToken ([https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name](https://www.w3.org/TR/1998/REC-xml-19980210#NT-Name))。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>, **bool**) | 當在衍生類別中被覆寫時，將讀取器的所有內容複製至寫入器，並將讀取器移至下一個同層節點的起始位置。 |
| virtual void [WriteNode](./writenode/)([SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>, **bool**) | 複製 XPathNavigator 物件的全部內容至寫入器。XPathNavigator 的位置保持不變。 |
| virtual void [WriteProcessingInstruction](./writeprocessinginstruction/)([String](../../system/string/), [String](../../system/string/)) | 當在衍生類別中被覆寫時，寫入一個處理指令，名稱與文字之間保留空格，如 **<?name text?>**。 |
| virtual void [WriteQualifiedName](./writequalifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具命名空間限定的名稱。此方法會查找該命名空間目前可用的前綴。 |
| virtual void [WriteRaw](./writeraw/)([ArrayPtr](../../system/arrayptr/)\<char16_t\>, **int32_t**, **int32_t**) | 當在衍生類別中被覆寫時，從字符緩衝區手動寫入原始標記。 |
| virtual void [WriteRaw](./writeraw/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，從字串手動寫入原始標記。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 寫入具有指定本地名稱與命名空間 URI 的屬性起始標記。 |
| virtual void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定前綴、本地名稱與命名空間 URI 的屬性起始標記。 |
| void [WriteStartAttribute](./writestartattribute/)(const [String](../../system/string/)\&) | 寫入具有指定本地名稱的屬性起始標記。 |
| virtual void [WriteStartDocument](./writestartdocument/)() | 當在衍生類別中被覆寫時，寫入版本為 \"1.0\" 的 XML 宣告。 |
| virtual void [WriteStartDocument](./writestartdocument/)(**bool**) | 當在衍生類別中被覆寫時，寫入版本為 \"1.0\" 且包含 standalone 屬性的 XML 宣告。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入指定的開始標籤並將其與給定的命名空間關聯。 |
| virtual void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入指定的開始標籤，並將其與給定的命名空間與前綴關聯。 |
| void [WriteStartElement](./writestartelement/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入具有指定本地名稱的開始標籤。 |
| virtual void [WriteString](./writestring/)(const [String](../../system/string/)\&) | 當在衍生類別中被覆寫時，寫入給定的文字內容。 |
| virtual void [WriteSurrogateCharEntity](./writesurrogatecharentity/)(char16_t, char16_t) | 當在衍生類別中被覆寫時，產生並寫入代理字元對的代理字符實體。 |
| virtual void [WriteValue](./writevalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 寫入物件的值。 |
| virtual void [WriteValue](./writevalue/)(const [String](../../system/string/)\&) | 寫入一個 [String](../../system/string/) 值。 |
| virtual void [WriteValue](./writevalue/)(**bool**) | 寫入一個 [Boolean](../../system/boolean/) 值。 |
| virtual void [WriteValue](./writevalue/)([DateTime](../../system/datetime/)) | 寫入一個 [DateTime](../../system/datetime/) 值。 |
| virtual void [WriteValue](./writevalue/)([DateTimeOffset](../../system/datetimeoffset/)) | 寫入一個 [DateTimeOffset](../../system/datetimeoffset/) 值。 |
| virtual void [WriteValue](./writevalue/)(**double**) | 寫入一個 [Double](../../system/double/) 值。 |
| virtual void [WriteValue](./writevalue/)(**float**) | 寫入單精度浮點數。 |
| virtual void [WriteValue](./writevalue/)([Decimal](../../system/decimal/)) | 寫入一個 [Decimal](../../system/decimal/) 值。 |
| virtual void [WriteValue](./writevalue/)(**int32_t**) | 寫入一個 [Int32](../../system/int32/) 值。 |
| virtual void [WriteValue](./writevalue/)(**int64_t**) | 寫入一個 [Int64](../../system/int64/) 值。 |
| virtual void [WriteWhitespace](./writewhitespace/)([String](../../system/string/)) | 當在衍生類別中被覆寫時，寫入給定的空白字元。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 參見

* 類別 [IDisposable](../../system/idisposable/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)