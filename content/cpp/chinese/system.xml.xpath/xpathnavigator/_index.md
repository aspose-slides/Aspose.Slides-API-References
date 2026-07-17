---
title: XPathNavigator
second_title: Aspose.Slides C++ API 参考
description: 提供用于导航和编辑 XML 数据的光标模型。
type: docs
weight: 66
url: /zh/system.xml.xpath/xpathnavigator/
---
## XPathNavigator 类

提供用于导航和编辑 XML 数据的光标模型。

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## 方法

| 方法 | 描述 |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | 返回一个用于在当前节点的子节点列表末尾创建一个或多个新子节点的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | 使用指定的 XML 数据字符串，在当前节点的子节点列表末尾创建一个新的子节点。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 对象的 XML 内容，在当前节点的子节点列表末尾创建一个新的子节点。 |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 中的节点，在当前节点的子节点列表末尾创建一个新的子节点。 |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空间前缀、本地名称和命名空间 URI 以及指定的值，在当前节点的子节点列表末尾创建一个新的子元素节点。 |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | 验证 [XPathNavigator](./) 中的 XML 数据是否符合提供的 XML [Schema](../../system.xml.schema/) 定义语言（XSD）模式。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | 在派生类中覆盖时，创建一个定位于与此 [XPathNavigator](./) 相同节点的新 [XPathNavigator](./)。 |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 比较当前 [XPathNavigator](./) 与指定的 [XPathNavigator](./) 的位置。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | 编译表示 [XPath](../) 表达式的字符串并返回一个 [XPathExpression](../xpathexpression/) 对象。 |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空间前缀、本地名称和命名空间 URI 以及指定的值，在当前元素节点上创建属性节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | 返回一个用于在当前元素上创建新属性的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | 返回 [XPathNavigator](./) 的副本。 |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 删除从当前节点到指定节点范围内的兄弟节点。 |
| virtual void [DeleteSelf](./deleteself/)() | 删除当前节点及其子节点。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | 使用 C# [Object.Equals](../../system/object/equals/) 语义比较对象。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较引用类型对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 以 C# 风格比较值类型对象。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 模拟 C# 风格的浮点比较，其中两个 NaN 被视为相等，即使根据 IEC 60559:1989，NaN 不等于任何值，包括 NaN 本身。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | 计算指定的 [XPath](../) 表达式并返回其类型化结果。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 计算指定的 [XPath](../) 表达式并返回其类型化结果，使用指定的 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 对象来解析 [XPath](../) 表达式中的命名空间前缀。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 计算 [XPathExpression](../xpathexpression/) 并返回其类型化结果。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | 使用提供的上下文评估 [XPathExpression](../xpathexpression/)，并返回其类型化结果。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 仅供内部使用。 |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | 在派生类中覆盖时，获取当前节点的基础 URI。 |
| virtual **bool** [get_CanEdit](./get_canedit/)() | 返回一个指示 [XPathNavigator](./) 是否能够编辑底层 XML 数据的值。 |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | 返回一个指示当前节点是否具有任何属性的值。 |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | 返回一个指示当前节点是否具有任何子节点的值。 |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | 返回表示当前节点子节点的标记。 |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | 在派生类中覆盖时，获取一个指示当前节点是否为没有结束标签的空元素的值。 |
| **bool** [get_IsNode](./get_isnode/)() override | 返回一个指示当前节点是否表示 [XPath](../) 节点的值。 |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | 在派生类中覆盖时，获取当前节点在不带任何命名空间前缀的 [XPathNavigator::get_Name](./get_name/)。 |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | 在派生类中覆盖时，获取当前节点的限定名称。 |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | 在派生类中覆盖时，获取当前节点的命名空间 URI。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | 在派生类中覆盖时，获取 [XPathNavigator](./) 的 [XmlNameTable](../../system.xml/xmlnametable/)。 |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | 返回一个用于比较 [XPathNavigator](./) 对象相等性的 [Collections::IEqualityComparer](../../system.collections/iequalitycomparer/)。 |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | 在派生类中覆盖时，获取当前节点的 XPathNodeType。 |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | 返回表示当前节点及其子节点的开闭标签的标记。 |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | 在派生类中覆盖时，获取与当前节点关联的命名空间前缀。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | 返回因模式验证而分配给当前节点的模式信息。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | 将当前节点作为最合适类型的装箱对象返回。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | 由提供“虚拟化”XML 视图的 [XPathNavigator](./) 实现使用，以访问底层对象。 |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | 在派生类中覆盖时，获取项的 **string** 值。 |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | 以 [Boolean](../../system/boolean/) 形式返回当前节点的值。 |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | 以 [DateTime](../../system/datetime/) 形式返回当前节点的值。 |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | 以 [Double](../../system/double/) 形式返回当前节点的值。 |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | 以 [Int32](../../system/int32/) 形式返回当前节点的值。 |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | 以 [Int64](../../system/int64/) 形式返回当前节点的值。 |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | 返回当前节点的类型。 |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | 返回 **xml:lang** 范围。 |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | 返回当前节点的 XmlSchemaType 信息。 |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | 返回具有指定本地名称和命名空间 URI 的属性的值。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | 获取与对象关联的引用计数器数据结构。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | 相当于 C# [Object.GetHashCode()](../../system/object/gethashcode/) 方法。启用自定义对象的哈希。 |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | 返回对应指定本地名称的命名空间节点的值。 |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | 返回当前节点的作用域内命名空间。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | 获取对象的实际类型。相当于 C# [System.Object.GetType()](../../system/object/gettype/) 调用。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | 返回一个用于在当前选定节点之后创建新兄弟节点的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | 使用指定的 XML 字符串，在当前选定节点之后创建一个新的兄弟节点。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 对象的 XML 内容，在当前选定节点之后创建一个新的兄弟节点。 |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 对象中的节点，在当前选定节点之后创建一个新的兄弟节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | 返回一个用于在当前选定节点之前创建新兄弟节点的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | 使用指定的 XML 字符串，在当前选定节点之前创建一个新的兄弟节点。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 对象的 XML 内容，在当前选定节点之前创建一个新的兄弟节点。 |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 中的节点，在当前选定节点之前创建一个新的兄弟节点。 |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空间前缀、本地名称和命名空间 URI 以及指定的值，在当前节点之后创建一个新的兄弟元素。 |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空间前缀、本地名称和命名空间 URI 以及指定的值，在当前节点之前创建一个新的兄弟元素。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | 检查对象是否表示由 targetType 描述的类型实例。相当于 C# 的 'is' 运算符。 |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 确定指定的 [XPathNavigator](./) 是否为当前 [XPathNavigator](./) 的后代。 |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 在派生类中覆盖时，确定当前 [XPathNavigator](./) 是否与指定的 [XPathNavigator](./) 位于相同位置。 |
| void [Lock](../../system/object/lock/)() | 实现 C# lock() 语句的加锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | 返回指定前缀的命名空间 URI。 |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | 返回为指定命名空间 URI 声明的前缀。 |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 确定当前节点是否匹配指定的 [XPathExpression](../xpathexpression/)。 |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | 确定当前节点是否匹配指定的 [XPath](../) 表达式。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | 相当于 C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) 方法。启用自定义类型的克隆。 |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到与指定的 [XPathNavigator](./) 相同的位置。 |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | 将 [XPathNavigator](./) 移动到具有匹配本地名称和命名空间 URI 的属性。 |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | 将 [XPathNavigator](./) 移动到具有指定本地名称和命名空间 URI 的子节点。 |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | 将 [XPathNavigator](./) 移动到指定 XPathNodeType 的子节点。 |
| virtual **bool** [MoveToFirst](./movetofirst/)() | 将 [XPathNavigator](./) 移动到当前节点的第一个兄弟节点。 |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到当前节点的第一个属性。 |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到当前节点的第一个子节点。 |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到匹配指定 XPathNamespaceScope 的第一个命名空间节点。 |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | 将 [XPathNavigator](./) 移动到当前节点的第一个命名空间节点。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | 将 [XPathNavigator](./) 按文档顺序移动到具有指定本地名称和命名空间 URI 的元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 将 [XPathNavigator](./) 按文档顺序移动到具有指定本地名称、命名空间 URI 和指定边界的元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | 将 [XPathNavigator](./) 按文档顺序移动到指定 XPathNodeType 的下一个元素。 |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 将 [XPathNavigator](./) 按文档顺序移动到指定 XPathNodeType 的下一元素，至指定边界。 |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | 在派生类中覆盖时，移动到具有类型为 **ID** 且值匹配指定 [String](../../system/string/) 的属性的节点。 |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | 将 [XPathNavigator](./) 移动到具有指定命名空间前缀的命名空间节点。 |
| virtual **bool** [MoveToNext](./movetonext/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到当前节点的下一个兄弟节点。 |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | 将 [XPathNavigator](./) 移动到具有指定本地名称和命名空间 URI 的下一个兄弟节点。 |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | 将 [XPathNavigator](./) 移动到匹配指定 XPathNodeType 的当前节点的下一个兄弟节点。 |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到下一个属性。 |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到匹配指定 XPathNamespaceScope 的下一个命名空间节点。 |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | 将 [XPathNavigator](./) 移动到下一个命名空间节点。 |
| virtual **bool** [MoveToParent](./movetoparent/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到当前节点的父节点。 |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | 在派生类中覆盖时，将 [XPathNavigator](./) 移动到当前节点的前一个兄弟节点。 |
| virtual void [MoveToRoot](./movetoroot/)() | 将 [XPathNavigator](./) 移动到当前节点所属的根节点。 |
|  [Object](../../system/object/object/)() | 创建对象。初始化所有内部数据结构。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | 复制构造函数。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 赋值运算符。实际上不复制任何内容，只是初始化新对象并允许子类复制构造。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | 返回一个用于在当前节点的子节点列表开头创建新子节点的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | 使用指定的 XML 字符串，在当前节点的子节点列表开头创建一个新的子节点。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 使用指定的 [XmlReader](../../system.xml/xmlreader/) 对象的 XML 内容，在当前节点的子节点列表开头创建一个新的子节点。 |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 使用指定的 [XPathNavigator](./) 对象中的节点，在当前节点的子节点列表开头创建一个新的子节点。 |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | 使用指定的命名空间前缀、本地名称和命名空间 URI 以及指定的值，在当前节点的子节点列表开头创建一个新的子元素。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | 返回一个包含当前节点及其子节点的 [XmlReader](../../system.xml/xmlreader/) 对象。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 通过引用比较对象。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 将值类型对象与 nullptr 进行引用比较。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 针对字符串和 nullptr 情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 针对字符串情形的 [Object::ReferenceEquals](../../system/object/referenceequals/) 特化。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 按指定值减少共享引用计数。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 替换从当前节点到指定节点范围内的兄弟节点。 |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | 用指定字符串的内容替换当前节点。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | 用指定的 [XmlReader](../../system.xml/xmlreader/) 对象的内容替换当前节点。 |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | 用指定的 [XPathNavigator](./) 对象的内容替换当前节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | 使用指定的 [XPath](../) 表达式选择节点集。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 使用指定的 [XPath](../) 表达式并使用 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 对象解析命名空间前缀，选择节点集。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 使用指定的 [XPathExpression](../xpathexpression/) 选择节点集。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | 选择当前节点所有具有匹配 XPathNodeType 的祖先节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | 选择当前节点所有具有指定本地名称和命名空间 URI 的祖先节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | 选择当前节点所有具有匹配 XPathNodeType 的子节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | 选择当前节点所有具有指定本地名称和命名空间 URI 的子节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | 选择当前节点所有具有匹配 XPathNodeType 的后代节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | 选择当前节点所有具有指定本地名称和命名空间 URI 的后代节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | 使用指定的 [XPath](../) 查询在 [XPathNavigator](./) 中选择单个节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | 使用指定的 [XPath](../) 查询并使用 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 对象解析命名空间前缀，在 [XPathNavigator](./) 对象中选择单个节点。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | 使用指定的 [XPathExpression](../xpathexpression/) 对象在 [XPathNavigator](./) 中选择单个节点。 |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | 设置表示当前节点子节点的标记。 |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | 设置表示当前节点及其子节点开闭标签的标记。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | 将第 n 个模板参数设为弱指针（而非共享）。允许在容器中切换指针为弱模式。 |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | 设置当前节点的类型化值。 |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | 设置当前节点的值。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 获取共享引用计数器的当前值。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 递增共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 递减并返回共享引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| [String](../../system/string/) [ToString](./tostring/)() const override | 返回当前节点的文本值。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | 实现 C# typeof([System.Object](../../system/object/)) 构造。 |
| void [Unlock](../../system/object/unlock/)() | 实现 C# lock() 语句的解锁。直接调用或使用 [LockContext](../../system/lockcontext/) 哨兵对象。 |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | 以指定的 Type 形式返回当前节点的值，使用指定的 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) 对象解析命名空间前缀。 |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | 以指定类型返回项的值。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 递增弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 递减弱引用计数。不要直接调用；请使用智能指针或 ThisProtector。 |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | 将当前节点及其子节点流式输出到指定的 [XmlWriter](../../system.xml/xmlwriter/) 对象。 |
| virtual  [~Object](../../system/object/~object/)() | 销毁对象。释放所有内部数据结构。 |

## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [Ptr](./ptr/) | 此类实例的共享指针的别名。 |

## 另见

* 类 [XPathItem](../xpathitem/)
* 类 [IXPathNavigable](../ixpathnavigable/)
* 类 [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* 命名空间 [System::Xml::XPath](../)
* 库 [Aspose.Slides](../../)