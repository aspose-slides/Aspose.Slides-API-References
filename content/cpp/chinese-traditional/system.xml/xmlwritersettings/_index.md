---
title: XmlWriterSettings
second_title: Aspose.Slides for C++ API 參考
description: "指定在由 XmlWriter::Create 方法建立的 XmlWriter 物件上支援的一組功能。"
type: docs
weight: 586
url: /zh-hant/system.xml/xmlwritersettings/
---
## XmlWriterSettings 類別


Specifies a set of features to support on the [XmlWriter](../xmlwriter/) object created by the [XmlWriter::Create](../xmlwriter/create/) method.

```cpp
class XmlWriterSettings : public System::Object
```

## 方法

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | 建立 [XmlWriterSettings](./) 實例的副本。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 被視為相等，即使根據 IEC 60559:1989，NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | 傳回一個值，以指示 XML 寫入器是否應檢查文件中的所有字元是否符合 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) 的「2.2 Characters」章節。 |
| **bool** [get_CloseOutput](./get_closeoutput/)() | 傳回一個值，以指示在呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法時，[XmlWriter](../xmlwriter/) 是否也應關閉底層的串流或 TextWriter。 |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | 傳回 XML 寫入器檢查 XML 輸出之符合性層級。 |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | 傳回一個值，以指示 [XmlWriter](../xmlwriter/) 是否不對 URI 屬性進行跳脫。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | 傳回要使用的文字編碼類型。 |
| **bool** [get_Indent](./get_indent/)() | 傳回一個值，以指示是否對元素縮排。 |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | 傳回縮排時使用的字元字串。當 [XmlWriterSettings::set_Indent](./set_indent/) 設為 **true** 時會使用此設定。 |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | 傳回一個值，以指示在寫入 XML 內容時，[XmlWriter](../xmlwriter/) 是否應移除重複的命名空間宣告。預設行為是寫入器會輸出其命名空間解析器中所有存在的命名空間宣告。 |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | 傳回用於換行的字元字串。 |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | 傳回一個值，以指示是否在輸出中正規化換行符號。 |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | 傳回一個值，以指示是否在新行寫入屬性。 |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | 傳回一個值，以指示是否省略 XML 宣告。 |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | 傳回用於序列化 [XmlWriter](../xmlwriter/) 輸出的方式。 |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | 傳回一個值，以指示在呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法時，[XmlWriter](../xmlwriter/) 是否會為所有未關閉的元素標籤添加關閉標籤。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。提供自訂物件的雜湊功能。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。提供自訂型別的克隆功能。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參考方式比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參考方式將值型別物件與 nullptr 比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特化版本，用於字串的情況。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參考計數減少指定的數值。 |
| void [Reset](./reset/)() | 將設定類別的成員重設為預設值。 |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | 設定一個值，以指示 XML 寫入器是否應檢查文件中的所有字元是否符合 W3C [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) 的「2.2 Characters」章節。 |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | 設定一個值，以指示在呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法時，[XmlWriter](../xmlwriter/) 是否也應關閉底層的串流或 TextWriter。 |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | 設定 XML 寫入器檢查 XML 輸出之符合性層級。 |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | 設定一個值，以指示 [XmlWriter](../xmlwriter/) 是否不對 URI 屬性進行跳脫。 |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | 設定要使用的文字編碼類型。 |
| void [set_Indent](./set_indent/)(**bool**) | 設定一個值，以指示是否對元素縮排。 |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | 設定縮排時使用的字元字串。當 [XmlWriterSettings::set_Indent](./set_indent/) 設為 **true** 時會使用此設定。 |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | 設定一個值，以指示在寫入 XML 內容時，[XmlWriter](../xmlwriter/) 是否應移除重複的命名空間宣告。預設行為是寫入器會輸出其命名空間解析器中所有存在的命名空間宣告。 |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | 設定用於換行的字元字串。 |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | 設定一個值，以指示是否在輸出中正規化換行符號。 |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | 設定一個值，以指示是否在新行寫入屬性。 |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | 設定一個值，以指示是否省略 XML 宣告。 |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | 設定一個值，以指示在呼叫 [XmlWriter::Close](../xmlwriter/close/) 方法時，[XmlWriter](../xmlwriter/) 是否會為所有未關閉的元素標籤添加關閉標籤。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設定為弱指標（而非共享）。允許在容器中將指標切換為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參考計數的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並回傳共享參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。提供將自訂物件轉換為字串的功能。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參考計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
|  [XmlWriterSettings](./xmlwritersettings/)() | 初始化 [XmlWriterSettings](./) 類別的新實例。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例之共享指標的別名。 |

## 備註



此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式配置。切勿在堆疊上或使用 new 運算子建立此類型的實例，否則會導致執行時錯誤和/或斷言失敗。請始終將此類別包裝成 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 另請參閱

* 類別 [Object](../../system/object/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)