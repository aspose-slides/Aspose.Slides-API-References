---
title: AddSort()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，根据指定的 IComparer 对象对 XPath 表达式选取的节点进行排序。
type: docs
weight: 27
url: /zh/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) 方法


在派生类中重写时，根据指定的 IComparer 对象对 [XPath](../../) 表达式选取的节点进行排序。

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 表示排序键的对象。它可以是节点的 **string** 值，或者是带有已编译的 [XPath](../../) 表达式的 [XPathExpression](../) 对象。 |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | 提供特定数据类型比较以比较两个对象是否相等的 IComparer 对象。 |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) 方法


在派生类中重写时，根据提供的参数对 [XPath](../../) 表达式选取的节点进行排序。

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 表示排序键的对象。它可以是节点的 **string** 值，或者是带有已编译的 [XPath](../../) 表达式的 [XPathExpression](../) 对象。 |
| order | [XmlSortOrder](../../xmlsortorder/) | 指示排序顺序的 XmlSortOrder 值。 |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | 指示如何对大小写字母进行排序的 XmlCaseOrder 值。 |
| lang | [String](../../../system/string/) | 用于比较的语言。使用可以传递给 [String::Compare](../../../system/string/compare/) 方法的语言类型的 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) 类，例如用于美式英语的 "us-en"。如果指定空字符串，则使用系统环境来确定 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/)。 |
| dataType | [XmlDataType](../../xmldatatype/) | 指示数据类型排序顺序的 XmlDataType 值。 |

## 另请参见

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Class [XPathExpression](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)