---
title: XPathNavigator
second_title: Aspose.Slides for C++ API Reference
description: Provides a cursor model for navigating and editing XML data.
type: docs
weight: 66
url: /system.xml.xpath/xpathnavigator/
---
## XPathNavigator class


Provides a cursor model for navigating and editing XML data.

```cpp
class XPathNavigator : public System::Xml::XPath::XPathItem,
                       public System::Xml::XPath::IXPathNavigable,
                       public System::Xml::IXmlNamespaceResolver
```

## Methods

| Method | Description |
| --- | --- |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [AppendChild](./appendchild/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create one or more new child nodes at the end of the list of child nodes of the current node. |
| virtual void [AppendChild](./appendchild/)([String](../../system/string/)) | Creates a new child node at the end of the list of child nodes of the current node using the XML data string specified. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Creates a new child node at the end of the list of child nodes of the current node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual void [AppendChild](./appendchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Creates a new child node at the end of the list of child nodes of the current node using the nodes in the [XPathNavigator](./) specified. |
| virtual void [AppendChildElement](./appendchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Creates a new child element node at the end of the list of child nodes of the current node using the namespace prefix, local name and namespace URI specified with the value specified. |
| virtual **bool** [CheckValidity](./checkvalidity/)([SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaSet](../../system.xml.schema/xmlschemaset/)\>, [System::Xml::Schema::ValidationEventHandler](../../system.xml.schema/validationeventhandler/)) | Verifies that the XML data in the [XPathNavigator](./) conforms to the XML [Schema](../../system.xml.schema/) definition language (XSD) schema provided. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [Clone](./clone/)() | When overridden in a derived class, creates a new [XPathNavigator](./) positioned at the same node as this [XPathNavigator](./). |
| virtual [XmlNodeOrder](../../system.xml/xmlnodeorder/) [ComparePosition](./compareposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Compares the position of the current [XPathNavigator](./) with the position of the [XPathNavigator](./) specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\> [Compile](./compile/)([String](../../system/string/)) | Compiles a string representing an [XPath](../) expression and returns an [XPathExpression](../xpathexpression/) object. |
| virtual void [CreateAttribute](./createattribute/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Creates an attribute node on the current element node using the namespace prefix, local name and namespace URI specified with the value specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [CreateAttributes](./createattributes/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create new attributes on the current element. |
| [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [CreateNavigator](./createnavigator/)() override | Returns a copy of the [XPathNavigator](./). |
| virtual void [DeleteRange](./deleterange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Deletes a range of sibling nodes from the current node to the node specified. |
| virtual void [DeleteSelf](./deleteself/)() | Deletes the current node and its child nodes. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/)) | Evaluates the specified [XPath](../) expression and returns the typed result. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Evaluates the specified [XPath](../) expression and returns the typed result, using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes in the [XPath](../) expression. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Evaluates the [XPathExpression](../xpathexpression/) and returns the typed result. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Evaluate](./evaluate/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>, [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\>) | Uses the supplied context to evaluate the [XPathExpression](../xpathexpression/), and returns the typed result. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| virtual [String](../../system/string/) [get_BaseURI](./get_baseuri/)() | When overridden in a derived class, gets the base URI for the current node. |
| virtual **bool** [get_CanEdit](./get_canedit/)() | Returns a value that indicates whether the [XPathNavigator](./) can edit the underlying XML data. |
| virtual **bool** [get_HasAttributes](./get_hasattributes/)() | Returns a value that indicates whether the current node has any attributes. |
| virtual **bool** [get_HasChildren](./get_haschildren/)() | Returns a value that indicates whether the current node has any child nodes. |
| virtual [String](../../system/string/) [get_InnerXml](./get_innerxml/)() | Returns the markup representing the child nodes of the current node. |
| virtual **bool** [get_IsEmptyElement](./get_isemptyelement/)() | When overridden in a derived class, gets a value that indicates whether the current node is an empty element without an end element tag. |
| **bool** [get_IsNode](./get_isnode/)() override | Returns a value that indicates if the current node represents an [XPath](../) node. |
| virtual [String](../../system/string/) [get_LocalName](./get_localname/)() | When overridden in a derived class, gets the [XPathNavigator::get_Name](./get_name/) of the current node without any namespace prefix. |
| virtual [String](../../system/string/) [get_Name](./get_name/)() | When overridden in a derived class, gets the qualified name of the current node. |
| virtual [String](../../system/string/) [get_NamespaceURI](./get_namespaceuri/)() | When overridden in a derived class, gets the namespace URI of the current node. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlNameTable](../../system.xml/xmlnametable/)\> [get_NameTable](./get_nametable/)() | When overridden in a derived class, gets the [XmlNameTable](../../system.xml/xmlnametable/) of the [XPathNavigator](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<[SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>\>\> [get_NavigatorComparer](./get_navigatorcomparer/)() | Returns an Collections::IEqualityComparer used for equality comparison of [XPathNavigator](./) objects. |
| virtual [XPathNodeType](../xpathnodetype/) [get_NodeType](./get_nodetype/)() | When overridden in a derived class, gets the XPathNodeType of the current node. |
| virtual [String](../../system/string/) [get_OuterXml](./get_outerxml/)() | Returns the markup representing the opening and closing tags of the current node and its child nodes. |
| virtual [String](../../system/string/) [get_Prefix](./get_prefix/)() | When overridden in a derived class, gets the namespace prefix associated with the current node. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::IXmlSchemaInfo](../../system.xml.schema/ixmlschemainfo/)\> [get_SchemaInfo](./get_schemainfo/)() | Returns the schema information that has been assigned to the current node as a result of schema validation. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_TypedValue](./get_typedvalue/)() override | Returns the current node as a boxed object of the most appropriate type. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UnderlyingObject](./get_underlyingobject/)() | Used by [XPathNavigator](./) implementations which provide a \"virtualized\" XML view over a store, to provide access to underlying objects. |
| virtual [String](../../system/string/) [get_Value](../xpathitem/get_value/)() | When overridden in a derived class, gets the **string** value of the item. |
| **bool** [get_ValueAsBoolean](./get_valueasboolean/)() override | Returns the current node's value as a [Boolean](../../system/boolean/). |
| [DateTime](../../system/datetime/) [get_ValueAsDateTime](./get_valueasdatetime/)() override | Returns the current node's value as a [DateTime](../../system/datetime/). |
| **double** [get_ValueAsDouble](./get_valueasdouble/)() override | Returns the current node's value as a [Double](../../system/double/). |
| **int32_t** [get_ValueAsInt](./get_valueasint/)() override | Returns the current node's value as an [Int32](../../system/int32/). |
| **int64_t** [get_ValueAsLong](./get_valueaslong/)() override | Returns the current node's value as an [Int64](../../system/int64/). |
| [TypeInfo](../../system/typeinfo/) [get_ValueType](./get_valuetype/)() override | Returns the type of the current node. |
| virtual [String](../../system/string/) [get_XmlLang](./get_xmllang/)() | Returns the **xml:lang** scope for the current node. |
| [SharedPtr](../../system/sharedptr/)\<[System::Xml::Schema::XmlSchemaType](../../system.xml.schema/xmlschematype/)\> [get_XmlType](./get_xmltype/)() override | Returns the XmlSchemaType information for the current node. |
| virtual [String](../../system/string/) [GetAttribute](./getattribute/)([String](../../system/string/), [String](../../system/string/)) | Returns the value of the attribute with the specified local name and namespace URI. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual [String](../../system/string/) [GetNamespace](./getnamespace/)([String](../../system/string/)) | Returns the value of the namespace node corresponding to the specified local name. |
| [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[String](../../system/string/), [String](../../system/string/)\>\> [GetNamespacesInScope](./getnamespacesinscope/)([XmlNamespaceScope](../../system.xml/xmlnamespacescope/)) override | Returns the in-scope namespaces of the current node. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertAfter](./insertafter/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new sibling node after the currently selected node. |
| virtual void [InsertAfter](./insertafter/)([String](../../system/string/)) | Creates a new sibling node after the currently selected node using the XML string specified. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Creates a new sibling node after the currently selected node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual void [InsertAfter](./insertafter/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Creates a new sibling node after the currently selected node using the nodes in the [XPathNavigator](./) object specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [InsertBefore](./insertbefore/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new sibling node before the currently selected node. |
| virtual void [InsertBefore](./insertbefore/)([String](../../system/string/)) | Creates a new sibling node before the currently selected node using the XML string specified. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Creates a new sibling node before the currently selected node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual void [InsertBefore](./insertbefore/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Creates a new sibling node before the currently selected node using the nodes in the [XPathNavigator](./) specified. |
| virtual void [InsertElementAfter](./insertelementafter/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Creates a new sibling element after the current node using the namespace prefix, local name and namespace URI specified, with the value specified. |
| virtual void [InsertElementBefore](./insertelementbefore/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Creates a new sibling element before the current node using the namespace prefix, local name, and namespace URI specified, with the value specified. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| virtual **bool** [IsDescendant](./isdescendant/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Determines whether the specified [XPathNavigator](./) is a descendant of the current [XPathNavigator](./). |
| virtual **bool** [IsSamePosition](./issameposition/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | When overridden in a derived class, determines whether the current [XPathNavigator](./) is at the same position as the specified [XPathNavigator](./). |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [String](../../system/string/) [LookupNamespace](./lookupnamespace/)(const [String](../../system/string/)\&) override | Returns the namespace URI for the specified prefix. |
| [String](../../system/string/) [LookupPrefix](./lookupprefix/)(const [String](../../system/string/)\&) override | Returns the prefix declared for the specified namespace URI. |
| virtual **bool** [Matches](./matches/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Determines whether the current node matches the specified [XPathExpression](../xpathexpression/). |
| virtual **bool** [Matches](./matches/)([String](../../system/string/)) | Determines whether the current node matches the specified [XPath](../) expression. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
| virtual **bool** [MoveTo](./moveto/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | When overridden in a derived class, moves the [XPathNavigator](./) to the same position as the specified [XPathNavigator](./). |
| virtual **bool** [MoveToAttribute](./movetoattribute/)([String](../../system/string/), [String](../../system/string/)) | Moves the [XPathNavigator](./) to the attribute with the matching local name and namespace URI. |
| virtual **bool** [MoveToChild](./movetochild/)([String](../../system/string/), [String](../../system/string/)) | Moves the [XPathNavigator](./) to the child node with the local name and namespace URI specified. |
| virtual **bool** [MoveToChild](./movetochild/)([XPathNodeType](../xpathnodetype/)) | Moves the [XPathNavigator](./) to the child node of the XPathNodeType specified. |
| virtual **bool** [MoveToFirst](./movetofirst/)() | Moves the [XPathNavigator](./) to the first sibling node of the current node. |
| virtual **bool** [MoveToFirstAttribute](./movetofirstattribute/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the first attribute of the current node. |
| virtual **bool** [MoveToFirstChild](./movetofirstchild/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the first child node of the current node. |
| virtual **bool** [MoveToFirstNamespace](./movetofirstnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | When overridden in a derived class, moves the [XPathNavigator](./) to the first namespace node that matches the XPathNamespaceScope specified. |
| **bool** [MoveToFirstNamespace](./movetofirstnamespace/)() | Moves the [XPathNavigator](./) to first namespace node of the current node. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/)) | Moves the [XPathNavigator](./) to the element with the local name and namespace URI specified in document order. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([String](../../system/string/), [String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Moves the [XPathNavigator](./) to the element with the local name and namespace URI specified, to the boundary specified, in document order. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/)) | Moves the [XPathNavigator](./) to the following element of the XPathNodeType specified in document order. |
| virtual **bool** [MoveToFollowing](./movetofollowing/)([XPathNodeType](../xpathnodetype/), [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Moves the [XPathNavigator](./) to the following element of the XPathNodeType specified, to the boundary specified, in document order. |
| virtual **bool** [MoveToId](./movetoid/)([String](../../system/string/)) | When overridden in a derived class, moves to the node that has an attribute of type **ID** whose value matches the specified [String](../../system/string/). |
| virtual **bool** [MoveToNamespace](./movetonamespace/)([String](../../system/string/)) | Moves the [XPathNavigator](./) to the namespace node with the specified namespace prefix. |
| virtual **bool** [MoveToNext](./movetonext/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the next sibling node of the current node. |
| virtual **bool** [MoveToNext](./movetonext/)([String](../../system/string/), [String](../../system/string/)) | Moves the [XPathNavigator](./) to the next sibling node with the local name and namespace URI specified. |
| virtual **bool** [MoveToNext](./movetonext/)([XPathNodeType](../xpathnodetype/)) | Moves the [XPathNavigator](./) to the next sibling node of the current node that matches the XPathNodeType specified. |
| virtual **bool** [MoveToNextAttribute](./movetonextattribute/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the next attribute. |
| virtual **bool** [MoveToNextNamespace](./movetonextnamespace/)([XPathNamespaceScope](../xpathnamespacescope/)) | When overridden in a derived class, moves the [XPathNavigator](./) to the next namespace node matching the XPathNamespaceScope specified. |
| **bool** [MoveToNextNamespace](./movetonextnamespace/)() | Moves the [XPathNavigator](./) to the next namespace node. |
| virtual **bool** [MoveToParent](./movetoparent/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the parent node of the current node. |
| virtual **bool** [MoveToPrevious](./movetoprevious/)() | When overridden in a derived class, moves the [XPathNavigator](./) to the previous sibling node of the current node. |
| virtual void [MoveToRoot](./movetoroot/)() | Moves the [XPathNavigator](./) to the root node that the current node belongs to. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [PrependChild](./prependchild/)() | Returns an [XmlWriter](../../system.xml/xmlwriter/) object used to create a new child node at the beginning of the list of child nodes of the current node. |
| virtual void [PrependChild](./prependchild/)([String](../../system/string/)) | Creates a new child node at the beginning of the list of child nodes of the current node using the XML string specified. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Creates a new child node at the beginning of the list of child nodes of the current node using the XML contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual void [PrependChild](./prependchild/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Creates a new child node at the beginning of the list of child nodes of the current node using the nodes in the [XPathNavigator](./) object specified. |
| virtual void [PrependChildElement](./prependchildelement/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Creates a new child element at the beginning of the list of child nodes of the current node using the namespace prefix, local name, and namespace URI specified with the value specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [ReadSubtree](./readsubtree/)() | Returns an [XmlReader](../../system.xml/xmlreader/) object that contains the current node and its child nodes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\> [ReplaceRange](./replacerange/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Replaces a range of sibling nodes from the current node to the node specified. |
| virtual void [ReplaceSelf](./replaceself/)([String](../../system/string/)) | Replaces the current node with the content of the string specified. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Replaces the current node with the contents of the [XmlReader](../../system.xml/xmlreader/) object specified. |
| virtual void [ReplaceSelf](./replaceself/)([SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\>) | Replaces the current node with the contents of the [XPathNavigator](./) object specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/)) | Selects a node set, using the specified [XPath](../) expression. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selects a node set using the specified [XPath](../) expression with the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [Select](./select/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selects a node set using the specified [XPathExpression](../xpathexpression/). |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([XPathNodeType](../xpathnodetype/), **bool**) | Selects all the ancestor nodes of the current node that have a matching XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectAncestors](./selectancestors/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selects all the ancestor nodes of the current node that have the specified local name and namespace URI. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([XPathNodeType](../xpathnodetype/)) | Selects all the child nodes of the current node that have the matching XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectChildren](./selectchildren/)([String](../../system/string/), [String](../../system/string/)) | Selects all the child nodes of the current node that have the local name and namespace URI specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([XPathNodeType](../xpathnodetype/), **bool**) | Selects all the descendant nodes of the current node that have a matching XPathNodeType. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNodeIterator](../xpathnodeiterator/)\> [SelectDescendants](./selectdescendants/)([String](../../system/string/), [String](../../system/string/), **bool**) | Selects all the descendant nodes of the current node with the local name and namespace URI specified. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/)) | Selects a single node in the [XPathNavigator](./) using the specified [XPath](../) query. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([String](../../system/string/), [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) | Selects a single node in the [XPathNavigator](./) object using the specified [XPath](../) query with the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[XPathNavigator](./)\> [SelectSingleNode](./selectsinglenode/)([SharedPtr](../../system/sharedptr/)\<[XPathExpression](../xpathexpression/)\>) | Selects a single node in the [XPathNavigator](./) using the specified [XPathExpression](../xpathexpression/) object. |
| virtual void [set_InnerXml](./set_innerxml/)([String](../../system/string/)) | Sets the markup representing the child nodes of the current node. |
| virtual void [set_OuterXml](./set_outerxml/)([String](../../system/string/)) | Sets the markup representing the opening and closing tags of the current node and its child nodes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| virtual void [SetTypedValue](./settypedvalue/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Sets the typed value of the current node. |
| virtual void [SetValue](./setvalue/)([String](../../system/string/)) | Sets the value of the current node. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Returns the text value of the current node. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](./valueas/)(const [TypeInfo](../../system/typeinfo/)\&, [SharedPtr](../../system/sharedptr/)\<[IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)\>) override | Returns the current node's value as the Type specified, using the [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/) object specified to resolve namespace prefixes. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [ValueAs](../xpathitem/valueas/)(const [TypeInfo](../../system/typeinfo/)\&) | Returns the item's value as the specified type. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual void [WriteSubtree](./writesubtree/)([SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>) | Streams the current node and its child nodes to the [XmlWriter](../../system.xml/xmlwriter/) object specified. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## See Also

* Class [XPathItem](../xpathitem/)
* Class [IXPathNavigable](../ixpathnavigable/)
* Class [IXmlNamespaceResolver](../../system.xml/ixmlnamespaceresolver/)
* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)