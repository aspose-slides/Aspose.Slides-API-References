---
title: AddSort()
second_title: Aspose.Slides for C++ API 參考文件
description: 當在衍生類別中被覆寫時，根據指定的 IComparer 物件對 XPath 表達式選取的節點進行排序。
type: docs
weight: 27
url: /zh-hant/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) 方法

When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the specified IComparer object.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 表示排序鍵的物件。它可以是節點的 **string** 值，或是帶有已編譯 [XPath](../../) 表達式的 [XPathExpression](../) 物件。 |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | 提供特定資料類型比較以比較兩個物件相等性的 IComparer 物件。 |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) 方法

When overridden in a derived class, sorts the nodes selected by the [XPath](../../) expression according to the supplied parameters.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 表示排序鍵的物件。它可以是節點的 **string** 值，或是帶有已編譯 [XPath](../../) 表達式的 [XPathExpression](../) 物件。 |
| order | [XmlSortOrder](../../xmlsortorder/) | 指示排序順序的 XmlSortOrder 值。 |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | 指示大小寫字母排序方式的 XmlCaseOrder 值。 |
| lang | [String](../../../system/string/) | 用於比較的語言。使用可傳遞給 [String::Compare](../../../system/string/compare/) 方法的 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) 類別以指定語言類型，例如 "us-en" 代表美式英語。若指定空字串，則使用系統環境來決定 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/)。 |
| dataType | [XmlDataType](../../xmldatatype/) | 指示資料類型排序順序的 XmlDataType 值。 |

## 另請參閱

* 列舉 [XmlSortOrder](../../xmlsortorder/)
* 列舉 [XmlCaseOrder](../../xmlcaseorder/)
* 列舉 [XmlDataType](../../xmldatatype/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Object](../../../system/object/)
* 類別 [IComparer](../../../system.collections.generic/icomparer/)
* 類別 [XPathExpression](../)
* 類別 [String](../../../system/string/)
* 命名空間 [System::Xml::XPath](../../)
* 函式庫 [Aspose.Slides](../../../)