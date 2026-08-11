---
title: MoveToFollowing()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينقل XPathNavigator إلى العنصر بالاسم المحلي وURI مساحة الاسم المحدد بترتيب المستند.
type: docs
weight: 703
url: /ar/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) method

Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | اسم العنصر المحلي. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للعنصر. |

### قيمة الإرجاع

**true** إذا تم نقل [XPathNavigator](../) بنجاح؛ وإلا، **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) method

Moves the [XPathNavigator](../) to the element with the local name and namespace URI specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| localName | [String](../../../system/string/) | اسم العنصر المحلي. |
| namespaceURI | [String](../../../system/string/) | URI مساحة الاسم للعنصر. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | الكائن [XPathNavigator](../) الموجود على حد العنصر والذي لن يتجاوز الكائن [XPathNavigator](../) الحالي أثناء البحث عن العنصر التالي. |

### قيمة الإرجاع

**true** إذا تم نقل [XPathNavigator](../) بنجاح؛ وإلا، **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) method

Moves the [XPathNavigator](../) to the following element of the XPathNodeType specified in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType للعنصر. لا يمكن أن يكون XPathNodeType هو [XPathNodeType::Attribute](../../xpathnodetype/) أو [XPathNodeType::Namespace](../../xpathnodetype/). |

### قيمة الإرجاع

**true** إذا تم نقل [XPathNavigator](../) بنجاح؛ وإلا، **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) method

Moves the [XPathNavigator](../) to the following element of the XPathNodeType specified, to the boundary specified, in document order.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | نوع XPathNodeType للعنصر. لا يمكن أن يكون XPathNodeType هو [XPathNodeType::Attribute](../../xpathnodetype/) أو [XPathNodeType::Namespace](../../xpathnodetype/). |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | الكائن [XPathNavigator](../) الموجود على حد العنصر والذي لن يتجاوز الكائن [XPathNavigator](../) الحالي أثناء البحث عن العنصر التالي. |

### قيمة الإرجاع

**true** إذا تم نقل [XPathNavigator](../) بنجاح؛ وإلا، **false**.

## انظر أيضًا

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)