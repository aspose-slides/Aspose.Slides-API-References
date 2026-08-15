---
title: XmlDocument
second_title: Aspose.Slides for C++ API 參考文件
description: 代表 XML 文件。您可以使用此類別來載入、驗證、編輯、添加以及定位文件中的 XML。
type: docs
weight: 183
url: /zh-hant/system.xml/xmldocument/
---
## XmlDocument 類別

代表一個 XML 文件。您可以使用此類別來載入、驗證、編輯、加入以及定位文件中的 XML。

```cpp
class XmlDocument : public System::Xml::XmlNode
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [AppendChild](../xmlnode/appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 將指定的節點新增至此節點的子節點清單的末端。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() | 取得指向集合中第一個元素（若有）的迭代器。由於 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的副本物件，故此迭代器無法用於變更所參照的物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [begin](../../system.collections.generic/ienumerable/begin/)() const | 取得指向集合之 const 限定實例中第一個元素（若有）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cbegin](../../system.collections.generic/ienumerable/cbegin/)() const | 取得指向集合中第一個 const 限定元素（若有）的迭代器。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [cend](../../system.collections.generic/ienumerable/cend/)() const | 取得指向集合中最後一個 const 限定元素（若有）之後的迭代器。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [Clone](../xmlnode/clone/)() | 建立此節點的副本。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CloneNode](./clonenode/)(**bool**) override | 建立此節點的副本。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&) | 建立具有指定名稱的 [XmlAttribute](../xmlattribute/)。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定限定名稱和 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlAttribute](../xmlattribute/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttribute](../xmlattribute/)\> [CreateAttribute](./createattribute/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定 [XmlNode::get_Prefix](../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](./get_localname/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlAttribute](../xmlattribute/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlCDataSection](../xmlcdatasection/)\> [CreateCDataSection](./createcdatasection/)(const [String](../../system/string/)\&) | 建立包含指定資料的 [XmlCDataSection](../xmlcdatasection/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlComment](../xmlcomment/)\> [CreateComment](./createcomment/)(const [String](../../system/string/)\&) | 建立包含指定資料的 [XmlComment](../xmlcomment/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentFragment](../xmldocumentfragment/)\> [CreateDocumentFragment](./createdocumentfragment/)() | 建立 [XmlDocumentFragment](../xmldocumentfragment/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [CreateDocumentType](./createdocumenttype/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 傳回一個新的 [XmlDocumentType](../xmldocumenttype/) 物件。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&) | 建立具有指定名稱的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有限定名稱與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlElement](../xmlelement/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [CreateElement](./createelement/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定 [XmlNode::get_Prefix](../xmlnode/get_prefix/)、[XmlDocument::get_LocalName](./get_localname/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的元素。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlEntityReference](../xmlentityreference/)\> [CreateEntityReference](./createentityreference/)(const [String](../../system/string/)\&) | 建立具有指定名稱的 [XmlEntityReference](../xmlentityreference/)。 |
| [SharedPtr](../../system/sharedptr/)\<[XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\> [CreateNavigator](./createnavigator/)() override | 建立新的 XPathNavigator 物件以導覽此文件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定 XmlNodeType、[XmlNode::get_Prefix](../xmlnode/get_prefix/)、[XmlDocument::get_Name](./get_name/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlNode](../xmlnode/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定節點類型、[XmlDocument::get_Name](./get_name/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlNode](../xmlnode/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [CreateNode](./createnode/)([XmlNodeType](../xmlnodetype/), const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定 XmlNodeType、[XmlDocument::get_Name](./get_name/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 的 [XmlNode](../xmlnode/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlProcessingInstruction](../xmlprocessinginstruction/)\> [CreateProcessingInstruction](./createprocessinginstruction/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定名稱與資料的 [XmlProcessingInstruction](../xmlprocessinginstruction/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlSignificantWhitespace](../xmlsignificantwhitespace/)\> [CreateSignificantWhitespace](./createsignificantwhitespace/)(const [String](../../system/string/)\&) | 建立 [XmlSignificantWhitespace](../xmlsignificantwhitespace/) 節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlText](../xmltext/)\> [CreateTextNode](./createtextnode/)(const [String](../../system/string/)\&) | 建立具有指定文字的 [XmlText](../xmltext/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWhitespace](../xmlwhitespace/)\> [CreateWhitespace](./createwhitespace/)(const [String](../../system/string/)\&) | 建立 [XmlWhitespace](../xmlwhitespace/) 節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDeclaration](../xmldeclaration/)\> [CreateXmlDeclaration](./createxmldeclaration/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | 建立具有指定值的 [XmlDeclaration](../xmldeclaration/) 節點。 |
| [iterator](../../system.collections.generic/ienumerable/iterator/) [end](../../system.collections.generic/ienumerable/end/)() | 取得指向集合中最後一個元素（若有）之後的迭代器。由於 [GetEnumerator()](../../system.collections.generic/ienumerable/getenumerator/) 會回傳 T 的副本物件，故此迭代器無法用於變更所參照的物件。 |
| [const_iterator](../../system.collections.generic/ienumerable/const_iterator/) [end](../../system.collections.generic/ienumerable/end/)() const | 取得指向集合之 const 限定實例中最後一個元素（若有）之後的迭代器。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語義比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 會被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點比較，兩個 NaN 會被視為相等，即使根據 IEC 60559:1989 NaN 不等於任何值，包括 NaN 本身。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlAttributeCollection](../xmlattributecollection/)\> [get_Attributes](../xmlnode/get_attributes/)() | 傳回包含此節點屬性的 [XmlAttributeCollection](../xmlattributecollection/)。 |
| [String](../../system/string/) [get_BaseURI](./get_baseuri/)() override | 傳回目前節點的基礎 URI。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [get_ChildNodes](../xmlnode/get_childnodes/)() | 傳回此節點的所有子節點。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [get_DocumentElement](./get_documentelement/)() | 傳回文件的根 [XmlElement](../xmlelement/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlDocumentType](../xmldocumenttype/)\> [get_DocumentType](./get_documenttype/)() | 傳回包含 DOCTYPE 宣告的節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_FirstChild](../xmlnode/get_firstchild/)() | 傳回節點的第一個子節點。 |
| virtual **bool** [get_HasChildNodes](../xmlnode/get_haschildnodes/)() | 傳回一個值，指示此節點是否具有任何子節點。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlImplementation](../xmlimplementation/)\> [get_Implementation](./get_implementation/)() | 傳回目前文件的 [XmlImplementation](../xmlimplementation/) 物件。 |
| virtual [String](../../system/string/) [get_InnerText](../xmlnode/get_innertext/)() | 傳回節點及其所有子節點的串接值。 |
| [String](../../system/string/) [get_InnerXml](./get_innerxml/)() override | 傳回表示目前節點子項的標記。 |
| **bool** [get_IsReadOnly](./get_isreadonly/)() override | 傳回一個值，指示目前節點是否唯讀。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_LastChild](../xmlnode/get_lastchild/)() | 傳回節點的最後一個子節點。 |
| [String](../../system/string/) [get_LocalName](./get_localname/)() override | 傳回節點的本機名稱。 |
| [String](../../system/string/) [get_Name](./get_name/)() override | 傳回節點的限定名稱。 |
| virtual [String](../../system/string/) [get_NamespaceURI](../xmlnode/get_namespaceuri/)() | 傳回此節點的命名空間 URI。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\> [get_NameTable](./get_nametable/)() | 傳回此實作所關聯的 [XmlNameTable](../xmlnametable/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_NextSibling](../xmlnode/get_nextsibling/)() | 傳回緊接此節點之後的節點。 |
| [XmlNodeType](../xmlnodetype/) [get_NodeType](./get_nodetype/)() override | 傳回目前節點的類型。 |
| virtual [String](../../system/string/) [get_OuterXml](../xmlnode/get_outerxml/)() | 傳回包含此節點及其所有子節點的標記。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlDocument](./)\> [get_OwnerDocument](./get_ownerdocument/)() override | 傳回目前節點所屬的 [XmlDocument](./)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_ParentNode](../xmlnode/get_parentnode/)() | 傳回此節點的父節點（適用於可以有父節點的節點）。 |
| virtual [String](../../system/string/) [get_Prefix](../xmlnode/get_prefix/)() | 傳回此節點的命名空間前綴。 |
| **bool** [get_PreserveWhitespace](./get_preservewhitespace/)() | 傳回一個值，指示是否在元素內容中保留空白字元。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousSibling](../xmlnode/get_previoussibling/)() | 傳回緊接此節點之前的節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [get_PreviousText](../xmlnode/get_previoustext/)() | 傳回緊接此節點之前的文字節點。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() override | 傳回節點的後綱驗證資訊集 (PSVI)。 |
| [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\> [get_Schemas](./get_schemas/)() | 傳回與此 [XmlDocument](./) 相關聯的 XmlSchemaSet 物件。 |
| virtual [String](../../system/string/) [get_Value](../xmlnode/get_value/)() | 傳回節點的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數資料結構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [GetElementById](./getelementbyid/)([String](../../system/string/)) | 傳回具有指定 ID 的 [XmlElement](../xmlelement/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/)) | 傳回包含所有符合指定名稱之子孫元素清單的 [XmlNodeList](../xmlnodelist/)。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [GetElementsByTagName](./getelementsbytagname/)([String](../../system/string/), [String](../../system/string/)) | 傳回包含所有符合指定 [XmlDocument::get_LocalName](./get_localname/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 之子孫元素清單的 [XmlNodeList](../xmlnodelist/)。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerator](../../system.collections.generic/ienumerator/)\<[SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\>\> [GetEnumerator](../xmlnode/getenumerator/)() override | 傳回一個可遍歷目前節點子節點的列舉器。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual [String](../../system/string/) [GetNamespaceOfPrefix](../xmlnode/getnamespaceofprefix/)([String](../../system/string/)) | 查找目前節點範圍內與給定前綴最接近的 **xmlns** 宣告，並回傳宣告中的命名空間 URI。 |
| virtual [String](../../system/string/) [GetPrefixOfNamespace](../xmlnode/getprefixofnamespace/)([String](../../system/string/)) | 查找目前節點範圍內與給定命名空間 URI 最接近的 **xmlns** 宣告，並回傳該宣告中定義的前綴。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/)) | 傳回具有指定 [XmlNode::get_Name](../xmlnode/get_name/) 的第一個子元素。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlElement](../xmlelement/)\> [idx_get](../xmlnode/idx_get/)([String](../../system/string/), [String](../../system/string/)) | 傳回具有指定 [XmlNode::get_LocalName](../xmlnode/get_localname/) 與 [XmlNode::get_NamespaceURI](../xmlnode/get_namespaceuri/) 值的第一個子元素。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ImportNode](./importnode/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, **bool**) | 將另一文件中的節點匯入至目前文件。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertAfter](../xmlnode/insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 在指定的參照節點之後立即插入指定的節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [InsertBefore](../xmlnode/insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 在指定的參照節點之前立即插入指定的節點。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否為 targetType 所描述類型的實例。相當於 C# 的 'is' 運算子。 |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | 對序列套用累加函式。 |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | 判斷序列的所有元素是否符合條件。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | 判斷序列是否包含任何元素。 |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | 判斷序列中是否存在任何元素或符合條件。 |
| T [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)() | 計算數值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 計算透過對輸入序列的每個元素呼叫轉換函式所取得之值序列的平均值。 |
| ResultType [LINQ_Average](../../system.collections.generic/ienumerable/linq_average/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | 將元素轉型為指定的類型。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | 串接兩個序列。 |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | 判斷序列是否包含指定的值。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | 傳回序列中元素的數量（透過直接計數計算）。 |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回序列中符合指定條件的元素數量。 |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | 傳回序列中指定索引位置的元素。 |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | 傳回序列中指定索引位置的元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | 傳回序列的第一個元素。 |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | 傳回符合指定條件之序列的第一個元素。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | 傳回序列的第一個元素；若序列為空則返回預設值。 |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | 傳回序列中符合條件的第一個元素；如果未找到此類元素，則傳回預設值。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | 將序列中的元素分組。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | 將序列中的元素分組。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | 傳回序列的最後一個元素。 |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | 傳回序列的最後一個元素；如果序列為空，則傳回預設值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素呼叫轉換函式，並傳回產生的最大值。 |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 對通用序列的每個元素呼叫轉換函式，並傳回產生的最小值。 |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | 根據指定類型過濾序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以升序排列序列中的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | 根據 keySelector 所選擇的鍵值，以降序排列序列中的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | 反轉序列中元素的順序。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | 轉換序列的元素。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | 將序列中的每個元素依其索引轉換為新形式。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | 對序列的每個元素進行投影，並將產生的序列合併為一個序列。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Skip](../../system.collections.generic/ienumerable/linq_skip/)(**int32_t**) | 跳過序列開頭指定數量的連續元素，並傳回其餘部分。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | 從序列開頭傳回指定數量的連續元素。 |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | 從序列建立陣列。 |
| [SharedPtr](../../system/sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | 從序列建立 List<T>。 |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | 根據指定的謂詞過濾序列。 |
| virtual void [Load](./load/)([String](../../system/string/)) | 從指定的 URL 載入 XML 文件。 |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | 從指定的串流載入 XML 文件。 |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | 從指定的 TextReader 載入 XML 文件。 |
| virtual void [Load](./load/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | 從指定的 [XmlReader](../xmlreader/) 載入 XML 文件。 |
| virtual void [LoadXml](./loadxml/)([String](../../system/string/)) | 從指定的字串載入 XML 文件。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。可對自訂型別進行克隆。 |
| virtual void [Normalize](../xmlnode/normalize/)() | 將此 [XmlNode](../xmlnode/) 底下子樹中全部 [XmlText](../xmltext/) 節點的完整深度轉換為「正常」形式，使僅有標記（即標籤、註解、處理指令、CDATA 區段與實體參照）分隔 [XmlText](../xmltext/) 節點，亦即不會有相鄰的 [XmlText](../xmltext/) 節點。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 指派運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [PrependChild](../xmlnode/prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 將指定的節點加入此節點的子節點清單開頭。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReadNode](./readnode/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../xmlreader/)\>) | 根據 [XmlReader](../xmlreader/) 中的資訊建立 [XmlNode](../xmlnode/) 物件。讀取器必須定位於節點或屬性上。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 以參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照比較值類型物件與 nullptr。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串與 nullptr 的情況。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 的特殊化，適用於字串的情況。 |
| virtual void [RemoveAll](../xmlnode/removeall/)() | 移除目前節點的所有子節點和/或屬性。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [RemoveChild](../xmlnode/removechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 移除指定的子節點。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共用參照計數減少指定的值。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [ReplaceChild](../xmlnode/replacechild/)([SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>, [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>) | 以 **newChild** 節點取代子節點 **oldChild**。 |
| virtual void [Save](./save/)([String](../../system/string/)) | 將 XML 文件儲存至指定檔案。若指定檔案已存在，則此方法會覆寫它。 |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | 將 XML 文件儲存至指定的串流。 |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>) | 將 XML 文件儲存至指定的 TextWriter。 |
| virtual void [Save](./save/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>) | 將 XML 文件儲存至指定的 [XmlWriter](../xmlwriter/)。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&) | 選取符合 [XPath](../../system.xml.xpath/) 表達式的節點清單。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNodeList](../xmlnodelist/)\> [SelectNodes](../xmlnode/selectnodes/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | 選取符合 [XPath](../../system.xml.xpath/) 表達式的節點清單。[XPath](../../system.xml.xpath/) 表達式中出現的任何前綴皆使用提供的 [XmlNamespaceManager](../xmlnamespacemanager/) 解析。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&) | 選取第一個符合 [XPath](../../system.xml.xpath/) 表達式的 [XmlNode](../xmlnode/)。 |
| [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\> [SelectSingleNode](../xmlnode/selectsinglenode/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[XmlNamespaceManager](../xmlnamespacemanager/)\>\&) | 選取第一個符合 [XPath](../../system.xml.xpath/) 表達式的 [XmlNode](../xmlnode/)。[XPath](../../system.xml.xpath/) 表達式中出現的任何前綴皆使用提供的 [XmlNamespaceManager](../xmlnamespacemanager/) 解析。 |
| void [set_InnerText](./set_innertext/)([String](../../system/string/)) override | 在任何情況下皆拋出 InvalidOperationException。 |
| void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) override | 設定表示目前節點子節點的標記。 |
| virtual void [set_Prefix](../xmlnode/set_prefix/)([String](../../system/string/)) | 設定此節點的命名空間前綴。 |
| void [set_PreserveWhitespace](./set_preservewhitespace/)(**bool**) | 設定是否在元素內容中保留空白字元的值。 |
| void [set_Schemas](./set_schemas/)(const [SharedPtr](../../system/sharedptr/)\<[Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>\&) | 設定與此 [XmlDocument](./) 關聯的 XmlSchemaSet 物件。 |
| virtual void [set_Value](../xmlnode/set_value/)([String](../../system/string/)) | 設定節點的值。 |
| virtual void [set_XmlResolver](./set_xmlresolver/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../xmlresolver/)\>) | 設定用於解析外部資源的 [XmlResolver](../xmlresolver/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為 weak 指標（而非 shared）。允許在容器中切換指標為弱模式。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得目前共用參照計數的值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共用參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共用參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| virtual **bool** [Supports](../xmlnode/supports/)([String](../../system/string/), [String](../../system/string/)) | 測試 DOM 實作是否支援特定功能。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | 相當於 C# [Object.ToString()](../../system/object/tostring/) 方法。可將自訂物件轉換為字串。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 建構式。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | 驗證 [XmlDocument](./) 是否符合 [XmlDocument::get_Schemas](./get_schemas/) 清單中所包含的 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 架構。 |
| void [Validate](./validate/)([Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/), const [SharedPtr](../../system/sharedptr/)\<[XmlNode](../xmlnode/)\>\&) | 驗證指定的 [XmlNode](../xmlnode/) 物件是否符合 [XmlDocument::get_Schemas](./get_schemas/) 清單中之 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 架構。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../../system.collections.generic/ienumerable/virtualizebeginconstiterator/)() const | 取得目前容器的 const begin 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../../system.collections.generic/ienumerable/virtualizebeginiterator/)() | 取得目前容器的 begin 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../../system.collections.generic/ienumerable/virtualizeendconstiterator/)() const | 取得目前容器的 const end 迭代器實作。 |
| virtual [virtualized_iterator](../../system.collections.generic/ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../../system.collections.generic/ienumerable/virtualizeenditerator/)() | 取得目前容器的 end 迭代器實作。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請使用智慧指標或 ThisProtector。 |
| void [WriteContentTo](./writecontentto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | 將 [XmlDocument](./) 節點的所有子節點儲存至指定的 [XmlWriter](../xmlwriter/)。 |
| void [WriteTo](./writeto/)(const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../xmlwriter/)\>\&) override | 將 [XmlDocument](./) 節點儲存至指定的 [XmlWriter](../xmlwriter/)。 |
|  [XmlDocument](./xmldocument/)() | 初始化 [XmlDocument](./) 類別的新執行個體。 |
|  [XmlDocument](./xmldocument/)(const [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../xmlnametable/)\>\&) | 使用指定的 [XmlNameTable](../xmlnametable/) 初始化 [XmlDocument](./) 類別的新執行個體。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的 shared pointer 別名。 |

## 備註

此類別的物件應僅使用 [System::MakeObject()](../../system/makeobject/) 函式分配。不要在堆疊或使用 new 運算子建立此類型的實例，因為會導致執行時錯誤和/或斷言失敗。始終將此類別封裝於 [System::SmartPtr](../../system/smartptr/) 指標，並使用該指標作為參數傳遞給函式。

## 另請參閱

* 類別 [XmlNode](../xmlnode/)
* 命名空間 [System::Xml](../)
* 函式庫 [Aspose.Slides](../../)