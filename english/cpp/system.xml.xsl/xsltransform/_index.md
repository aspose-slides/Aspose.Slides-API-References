---
title: XslTransform
second_title: Aspose.Slides for C++ API Reference
description: Transforms XML data using an Extensible Stylesheet Language for Transformations (XSLT) style sheet.
type: docs
weight: 105
url: /cpp/system.xml.xsl/xsltransform/
---
## XslTransform class


Transforms XML data using an Extensible Stylesheet Language for Transformations (XSLT) style sheet.

```cpp
class XslTransform : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compares objects using C# [Object.Equals](../../system/object/equals/) semantics. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares reference type objects in C# style. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compares value type objects in C# style. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | For internal purposes only. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Gets reference counter data structure associated with the object. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Gets actual type of object. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&) | Loads the XSLT style sheet contained in the [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Loads the XSLT style sheet contained in the [XmlReader](../../system.xml/xmlreader/). |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&) | Loads the XSLT style sheet contained in the IXPathNavigable. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Loads the XSLT style sheet contained in the IXPathNavigable. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&) | Loads the XSLT style sheet contained in the XPathNavigator. |
| void [Load](./load/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Loads the XSLT style sheet contained in the XPathNavigator. |
| void [Load](./load/)(const [String](../../system/string/)\&) | Loads the XSLT style sheet specified by a URL. |
| void [Load](./load/)(const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Loads the XSLT style sheet specified by a URL. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | Creates object. Initializes all internal data structures. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compares objects by reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Decreases shared reference count by specified value. |
| void [set_XmlResolver](./set_xmlresolver/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Sets the [XmlResolver](../../system.xml/xmlresolver/) used to resolve external resources when the [XslTransform::Transform](./transform/) method is called. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Set n'th template argument a weak pointer (rather than shared). Allows switching pointers in containers to weak mode. |
| int [SharedCount](../../system/object/sharedcount/)() const | Gets current value of shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Increments shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrements and returns shared reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Transforms the XML data in the XPathNavigator using the specified args and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../system.xml.xpath/xpathnavigator/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Transforms the XML data in the XPathNavigator using the specified **args** and outputs the result to a TextWriter. |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| [SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\> [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlReader](../../system.xml/xmlreader/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a TextWriter. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to a Stream. |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../system.xml.xpath/ixpathnavigable/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XsltArgumentList](../xsltargumentlist/)\>\&, const [SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>\&) | Transforms the XML data in the IXPathNavigable using the specified **args** and outputs the result to an [XmlWriter](../../system.xml/xmlwriter/). |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [SharedPtr](../../system/sharedptr/)\<[System::Xml::XmlResolver](../../system.xml/xmlresolver/)\>\&) | Transforms the XML data in the input file and outputs the result to an output file. |
| void [Transform](./transform/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Transforms the XML data in the input file and outputs the result to an output file. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
|  [XslTransform](./xsltransform/)() | Initializes a new instance of the [XslTransform](./) class. |
| virtual  [~Object](../../system/object/~object/)() | Destroys object. Frees all internal data structures. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [Ptr](./ptr/) | An alias for shared pointer to an instance of this class. |
## Remarks



Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instances of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument. 

## See Also

* Class [Object](../../system/object/)
* Namespace [System::Xml::Xsl](../)
* Library [Aspose.Slides](../../)
