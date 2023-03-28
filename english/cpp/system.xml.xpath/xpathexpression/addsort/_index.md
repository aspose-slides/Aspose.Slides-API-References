---
title: AddSort()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, sorts the nodes selected by the XPath expression according to the specified IComparer object.
type: docs
weight: 27
url: /cpp/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort([SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>, [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>) method


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the specified IComparer object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | An object representing the sort key. This can be the **string** value of the node or an [XPathExpression](../) object with a compiled [XPath](../../) expression. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | An IComparer object that provides the specific data type comparisons for comparing two objects for equivalence. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
## XPathExpression::AddSort([SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>, [XmlSortOrder](../../xmlsortorder/), [XmlCaseOrder](../../xmlcaseorder/), [String](../../../system/string/), [XmlDataType](../../xmldatatype/)) method


When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the supplied parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | An object representing the sort key. This can be the **string** value of the node or an [XPathExpression](../) object with a compiled [XPath](../../) expression. |
| order | [XmlSortOrder](../../xmlsortorder/) | An XmlSortOrder value indicating the sort order. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | An XmlCaseOrder value indicating how to sort uppercase and lowercase letters. |
| lang | [String](../../../system/string/) | The language to use for comparison. Uses the [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) class that can be passed to the [String::Compare](../../../system/string/compare/) method for the language types, for example, \"us-en\" for U.S. English. If an empty string is specified, the system environment is used to determine the [Globalization::CultureInfo](../../../system.globalization/cultureinfo/). |
| dataType | [XmlDataType](../../xmldatatype/) | An XmlDataType value indicating the sort order for the data type. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Class [String](../../../system/string/)
* Enum [XmlDataType](../../xmldatatype/)
* Class [XPathExpression](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)
