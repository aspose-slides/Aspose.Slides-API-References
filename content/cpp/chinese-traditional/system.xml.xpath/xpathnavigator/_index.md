---
title: XPathNavigator
second_title: Aspose.Slides for C++ API 參考
description: 提供一種游標模型，用於瀏覽和編輯 XML 資料。
type: docs
weight: 66
url: /zh-hant/system.xml.xpath/xpathnavigator/
---
## XPathNavigator 類別

Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 說明 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | 傳回一個 [XmlWriter](../../system.xml/xmlwriter/) 物件，用於在目前節點的子節點清單末端建立一個或多個新子節點。 |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | 使用指定的 XML 資料字串，在目前節點的子節點清單末端建立一個新子節點。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 物件之 XML 內容，在目前節點的子節點清單末端建立一個新子節點。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 中的節點，在目前節點的子節點清單末端建立一個新子節點。 |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的名稱空間前置詞、本機名稱與名稱空間 URI 以及指定的值，在目前節點的子節點清單末端建立一個新子元素節點。 |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | 驗證 [XPathNavigator](./) 中的 XML 資料是否符合提供的 XML [Schema](../../system.xml.schema/) 定義語言 (XSD) 綱要。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | 在衍生類別中覆寫時，建立一個與此 [XPathNavigator](./) 位於相同節點的新 [XPathNavigator](./)。 |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 比較目前 [XPathNavigator](./) 與指定的 [XPathNavigator](./) 位置。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | 編譯表示 [XPath](../) 運算式的字串，並傳回一個 [XPathExpression](../xpathexpression/) 物件。 |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的名稱空間前置詞、本機名稱與名稱空間 URI 以及指定的值，在目前的元素節點上建立屬性節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | 傳回用於在目前元素上建立新屬性的 [XmlWriter](../../system.xml/xmlwriter/) 物件。 |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | 傳回 [XPathNavigator](./) 的副本。 |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 刪除從目前節點到指定節點之間的一系列同級節點。 |
| virtual void [DeleteSelf](./deleteself/)() | 刪除目前節點及其子節點。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 語意比較物件。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較參考型別的物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 風格比較值型別的物件。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）均不相等。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模擬 C# 風格的浮點數比較，將兩個 NaN 視為相等，即使根據 IEC 60559:1989，NaN 與任何值（包括 NaN）均不相等。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | 評估指定的 [XPath](../) 運算式，並傳回具類型的結果。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 評估指定的 [XPath](../) 運算式並傳回具類型的結果，使用指定的 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 物件來解析 [XPath](../) 運算式中的名稱空間前置詞。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 評估 [XPathExpression](../xpathexpression/)，並傳回具類型的結果。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | 使用提供的上下文評估 [XPathExpression](../xpathexpression/)，並傳回具類型的結果。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 僅供內部使用。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 在衍生類別中覆寫時，取得目前節點的基礎 URI。 |
| virtual **bool** [get_CanEdit](./get_canedit/)() | 傳回一個值，指示 [XPathNavigator](./) 是否能編輯底層 XML 資料。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 傳回一個值，指示目前節點是否具有任何屬性。 |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | 傳回一個值，指示目前節點是否具有任何子節點。 |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | 傳回表示目前節點子節點的標記。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 在衍生類別中覆寫時，取得指示目前節點是否為沒有結束標籤的空元素的值。 |
| **bool** [get_IsNode](./get_isnode/)() override | 傳回一個值，指示目前節點是否代表 [XPath](../) 節點。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 在衍生類別中覆寫時，取得目前節點不含任何名稱空間前置詞的 [XPathNavigator::get_Name](./get_name/)。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 在衍生類別中覆寫時，取得目前節點的合格名稱。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 在衍生類別中覆寫時，取得目前節點的名稱空間 URI。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 在衍生類別中覆寫時，取得 [XPathNavigator](./) 的 [XmlNameTable](../../system.xml/xmlnametable/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | 傳回用於比較 [XPathNavigator](./) 物件相等性的 [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/)。 |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | 在衍生類別中覆寫時，取得目前節點的 XPathNodeType。 |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | 傳回表示目前節點及其子節點的起始與結束標籤的標記。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 在衍生類別中覆寫時，取得與目前節點相關聯的名稱空間前置詞。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 傳回因為綱要驗證而指派給目前節點的綱要資訊。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | 將目前節點以最合適的類型封裝成物件並傳回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | 供提供「虛擬化」XML 檢視於儲存區的 [XPathNavigator](./) 實作使用，以存取底層物件。 |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | 在衍生類別中覆寫時，取得項目的 **string** 值。 |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | 傳回目前節點的值，作為 [Boolean](../../system/boolean/)。 |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | 傳回目前節點的值，作為 [DateTime](../../system/datetime/)。 |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | 傳回目前節點的值，作為 [Double](../../system/double/)。 |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | 傳回目前節點的值，作為 [Int32](../../system/int32/)。 |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | 傳回目前節點的值，作為 [Int64](../../system/int64/)。 |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | 傳回目前節點的類型。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 傳回目前節點的 **xml:lang** 範圍。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | 傳回目前節點的 XmlSchemaType 資訊。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 傳回具有指定本機名稱與名稱空間 URI 的屬性值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 取得與物件相關聯的參考計數器資料結構。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相當於 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。啟用自訂物件的雜湊。 |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | 傳回對應指定本機名稱之名稱空間節點的值。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | 傳回目前節點的可見名稱空間。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 取得物件的實際類型。相當於 C# [System.Object.GetType()](../../system/object/gettype/) 呼叫。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | 傳回用於在目前選取的節點之後建立新同級節點的 [XmlWriter](../../system.xml/xmlwriter/) 物件。 |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | 使用指定的 XML 字串，在目前選取的節點之後建立新同級節點。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 物件之 XML 內容，在目前選取的節點之後建立新同級節點。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 物件中的節點，在目前選取的節點之後建立新同級節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | 傳回用於在目前選取的節點之前建立新同級節點的 [XmlWriter](../../system.xml/xmlwriter/) 物件。 |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | 使用指定的 XML 字串，在目前選取的節點之前建立新同級節點。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 物件之 XML 內容，在目前選取的節點之前建立新同級節點。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 中的節點，在目前選取的節點之前建立新同級節點。 |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的名稱空間前置詞、本機名稱與名稱空間 URI 以及指定的值，在目前節點之後建立新同級元素。 |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的名稱空間前置詞、本機名稱與名稱空間 URI 以及指定的值，在目前節點之前建立新同級元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 檢查物件是否代表 targetType 所描述的型別實例。相當於 C# 的 'is' 運算子。 |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 判斷指定的 [XPathNavigator](./) 是否為目前 [XPathNavigator](./) 的子代。 |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 在衍生類別中覆寫時，判斷目前的 [XPathNavigator](./) 是否與指定的 [XPathNavigator](./) 位於相同位置。 |
| void [Lock](../../system/object/lock/)() | 實作 C# lock() 陳述式的鎖定。直接呼叫或使用 [LockContext](../../system/lockcontext/) 監視物件。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 傳回指定前置詞的名稱空間 URI。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | 傳回指定名稱空間 URI 所宣告的前置詞。 |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 判斷目前節點是否符合指定的 [XPathExpression](../xpathexpression/)。 |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | 判斷目前節點是否符合指定的 [XPath](../) 運算式。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相當於 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。啟用自訂型別的克隆。 |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動至與指定的 [XPathNavigator](./) 相同位置。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | 將 [XPathNavigator](./) 移動至具有相符本機名稱與名稱空間 URI 的屬性。 |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | 將 [XPathNavigator](./) 移動至具有指定本機名稱與名稱空間 URI 的子節點。 |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | 將 [XPathNavigator](./) 移動至指定 XPathNodeType 的子節點。 |
| virtual **bool** [MoveToFirst](./movetofirst/)() | 將 [XPathNavigator](./) 移動至目前節點的第一個同級節點。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動至目前節點的第一個屬性。 |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動至目前節點的第一個子節點。 |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動至第一個符合指定 XPathNamespaceScope 的名稱空間節點。 |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | 將 [XPathNavigator](./) 移動到當前節點的第一個命名空間節點。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | 將 [XPathNavigator](./) 移動到文件順序中指定本地名稱和命名空間 URI 的元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 將 [XPathNavigator](./) 移動到文件順序中指定本地名稱和命名空間 URI，且位於指定邊界的元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | 將 [XPathNavigator](./) 移動到文件順序中指定 XPathNodeType 的下一個元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 將 [XPathNavigator](./) 移動到文件順序中指定 XPathNodeType 且位於指定邊界的下一個元素。 |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | 在衍生類別中覆寫時，移動到具有類型為 **ID** 且其值符合指定 [String](../../system/string/) 的屬性的節點。 |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | 將 [XPathNavigator](./) 移動到具有指定命名空間前綴的命名空間節點。 |
| virtual **bool** [MoveToNext](./movetonext/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動到當前節點的下一個兄弟節點。 |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | 將 [XPathNavigator](./) 移動到具有指定本地名稱和命名空間 URI 的下一個兄弟節點。 |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | 將 [XPathNavigator](./) 移動到當前節點中符合指定 XPathNodeType 的下一個兄弟節點。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動到下一個屬性。 |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動到匹配指定 XPathNamespaceScope 的下一個命名空間節點。 |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | 將 [XPathNavigator](./) 移動到下一個命名空間節點。 |
| virtual **bool** [MoveToParent](./movetoparent/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動到當前節點的父節點。 |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | 在衍生類別中覆寫時，將 [XPathNavigator](./) 移動到當前節點的前一個兄弟節點。 |
| virtual void [MoveToRoot](./movetoroot/)() | 將 [XPathNavigator](./) 移動到當前節點所屬的根節點。 |
|  [Object](../../system/object/object/)() | 建立物件。初始化所有內部資料結構。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 複製建構函式。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 賦值運算子。實際上不會複製任何內容，只是初始化新物件並允許子類別的複製建構。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | 傳回一個 [XmlWriter](../../system.xml/xmlwriter/) 物件，用於在當前節點的子節點列表開頭建立新子節點。 |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | 使用指定的 XML 字串在當前節點的子節點列表開頭建立新子節點。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 物件之 XML 內容，在當前節點的子節點列表開頭建立新子節點。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 物件中的節點，在當前節點的子節點列表開頭建立新子節點。 |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空間前綴、本地名稱與命名空間 URI，以及指定的值，在當前節點的子節點列表開頭建立新子元素。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | 傳回一個包含當前節點及其子節點的 [XmlReader](../../system.xml/xmlreader/) 物件。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 依參照比較物件。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 以參照方式將值型別物件與 nullptr 進行比較。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串與 nullptr 情況下的特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) 在字串情況下的特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 將共享參照計數減少指定的值。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 取代從當前節點到指定節點之間的一系列兄弟節點。 |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | 以指定字串的內容取代當前節點。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 以指定的 [XmlReader](../../system.xml/xmlreader/) 物件之內容取代當前節點。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 以指定的 [XPathNavigator](./) 物件之內容取代當前節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | 使用指定的 [XPath](../) 表達式選取節點集合。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 使用指定的 [XPath](../) 表達式，並以 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 物件解析命名空間前綴，選取節點集合。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 使用指定的 [XPathExpression](../xpathexpression/) 選取節點集合。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | 選取所有與指定 XPathNodeType 相符的當前節點之祖先節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | 選取所有具有指定本地名稱和命名空間 URI 的當前節點之祖先節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | 選取所有與指定 XPathNodeType 相符的當前節點之子節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | 選取所有具有指定本地名稱與命名空間 URI 的當前節點之子節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | 選取所有與指定 XPathNodeType 相符的當前節點之子孫節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | 選取所有具有指定本地名稱與命名空間 URI 的當前節點之子孫節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | 在 [XPathNavigator](./) 中使用指定的 [XPath](../) 查詢選取單一節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 在 [XPathNavigator](./) 物件中使用指定的 [XPath](../) 查詢，並以 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 物件解析命名空間前綴，選取單一節點。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 在 [XPathNavigator](./) 中使用指定的 [XPathExpression](../xpathexpression/) 物件，選取單一節點。 |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | 設定代表當前節點子節點的標記。 |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | 設定代表當前節點及其子節點的開閉標籤的標記。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 將第 n 個模板參數設為弱指標（而非共享指標）。允許在容器中切換指標為弱模式。 |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 設定當前節點的具型別值。 |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | 設定當前節點的值。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 取得共享參照計數器的目前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 遞增共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 遞減並傳回共享參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 傳回當前節點的文字值。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 實作 C# typeof([System.Object](../../system/object/)) 結構。 |
| void [Unlock](../../system/object/unlock/)() | 實作 C# lock() 陳述式的解鎖。可直接呼叫或使用 [LockContext](../../system/lockcontext/) 看守物件。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | 傳回當前節點的值為指定的 Type，並使用指定的 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 物件解析命名空間前綴。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | 傳回項目的值為指定的型別。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 遞增弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 遞減弱參照計數。不應直接呼叫；請改用智慧指標或 ThisProtector。 |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | 將當前節點及其子節點串流至指定的 [XmlWriter](../../system.xml/xmlwriter/) 物件。 |
| virtual  [~Object](../../system/object/~object/)() | 銷毀物件。釋放所有內部資料結構。 |

## 型別別名

| 型別別名 | 說明 |
| --- | --- |
| [Ptr](./ptr/) | 此類別實例的共享指標別名。 |

## 另見

* 類別 [XPathItem](../xpathitem/)
* 類別 [IXPathNavigable](../ixpathnavigable/)
* 類別 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* 命名空間 [System::Xml::XPath](../)
* 函式庫 [Aspose.Slides](../../)