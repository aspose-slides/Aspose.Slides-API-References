---
title: Select()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XPath 식을 사용하여 노드 집합을 선택합니다.
type: docs
weight: 794
url: /ko/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) 메서드

지정된 [XPath](../../) 식을 사용하여 노드 집합을 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/)은 [XPath](../../) 식을 나타냅니다. |

### 반환 값

선택된 노드 집합을 가리키는 [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) 메서드

지정된 [XPath](../../) 식과 네임스페이스 접두사를 해석하기 위해 지정된 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 노드 집합을 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/)은 [XPath](../../) 식을 나타냅니다. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | 네임스페이스 접두사를 해석하는 데 사용되는 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체. |

### 반환 값

선택된 노드 집합을 가리키는 [XPathNodeIterator](../../xpathnodeiterator/).

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) 메서드

지정된 [XPathExpression](../../xpathexpression/)를 사용하여 노드 집합을 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | 컴파일된 [XPath](../../) 쿼리를 포함하는 [XPathExpression](../../xpathexpression/) 객체. |

### 반환 값

선택된 노드 집합을 가리키는 [XPathNodeIterator](../../xpathnodeiterator/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNodeIterator](../../xpathnodeiterator/)
* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XPathExpression](../../xpathexpression/)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)