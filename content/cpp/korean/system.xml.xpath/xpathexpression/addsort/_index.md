---
title: AddSort()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 지정된 IComparer 객체에 따라 XPath 식으로 선택된 노드를 정렬합니다.
type: docs
weight: 27
url: /ko/system.xml.xpath/xpathexpression/addsort/
---
## XPathExpression::AddSort(SharedPtr\<Object\>, SharedPtr\<Collections::Generic::IComparer\<SharedPtr\<Object\>\>\>) 메서드

파생 클래스에서 재정의될 경우, 지정된 IComparer 객체에 따라 [XPath](../../) 식으로 선택된 노드를 정렬합니다.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, SharedPtr<Collections::Generic::IComparer<SharedPtr<Object>>> comparer)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 정렬 키를 나타내는 객체입니다. 노드의 **string** 값이거나 컴파일된 [XPath](../../) 식을 가진 [XPathExpression](../) 객체일 수 있습니다. |
| comparer | [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IComparer](../../../system.collections.generic/icomparer/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\> | 두 객체의 동등성을 비교하기 위해 특정 데이터 형식 비교를 제공하는 IComparer 객체입니다. |

## XPathExpression::AddSort(SharedPtr\<Object\>, XmlSortOrder, XmlCaseOrder, String, XmlDataType) 메서드

파생 클래스에서 재정의될 경우, 제공된 매개변수에 따라 [XPath](../../) 식으로 선택된 노드를 정렬합니다.

```cpp
virtual void System::Xml::XPath::XPathExpression::AddSort(SharedPtr<Object> expr, XmlSortOrder order, XmlCaseOrder caseOrder, String lang, XmlDataType dataType)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 정렬 키를 나타내는 객체입니다. 노드의 **string** 값이거나 컴파일된 [XPath](../../) 식을 가진 [XPathExpression](../) 객체일 수 있습니다. |
| order | [XmlSortOrder](../../xmlsortorder/) | 정렬 순서를 나타내는 XmlSortOrder 값입니다. |
| caseOrder | [XmlCaseOrder](../../xmlcaseorder/) | 대소문자 정렬 방식을 나타내는 XmlCaseOrder 값입니다. |
| lang | [String](../../../system/string/) | 비교에 사용할 언어입니다. 예를 들어 미국 영어의 "us-en"과 같이 언어 유형을 위해 [String::Compare](../../../system/string/compare/) 메서드에 전달될 수 있는 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/) 클래스를 사용합니다. 빈 문자열이 지정되면 시스템 환경을 사용하여 [Globalization::CultureInfo](../../../system.globalization/cultureinfo/)을 결정합니다. |
| dataType | [XmlDataType](../../xmldatatype/) | 데이터 형식에 대한 정렬 순서를 나타내는 XmlDataType 값입니다. |

## 참고

* Enum [XmlSortOrder](../../xmlsortorder/)
* Enum [XmlCaseOrder](../../xmlcaseorder/)
* Enum [XmlDataType](../../xmldatatype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [IComparer](../../../system.collections.generic/icomparer/)
* 클래스 [XPathExpression](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)