---
title: SelectSingleNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 XPath 쿼리를 사용하여 XPathNavigator에서 단일 노드를 선택합니다.
type: docs
weight: 781
url: /ko/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) 메서드

[XPathNavigator](../)에서 지정된 [XPath](../../) 쿼리를 사용하여 단일 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/)는 [XPath](../../) 식을 나타냅니다. |

### 반환 값

지정된 [XPath](../../) 쿼리에 대해 첫 번째 일치하는 노드를 포함하는 [XPathNavigator](../) 객체이며, 쿼리 결과가 없을 경우 **nullptr**를 반환합니다.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) 메서드

[XPathNavigator](../) 객체에서 지정된 [XPath](../../) 쿼리를 사용하고, 네임스페이스 접두사를 해결하기 위해 지정된 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체를 사용하여 단일 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | [String](../../../system/string/)는 [XPath](../../) 식을 나타냅니다. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) 객체는 [XPath](../../) 쿼리에서 네임스페이스 접두사를 해결하는 데 사용됩니다. |

### 반환 값

지정된 [XPath](../../) 쿼리에 대해 첫 번째 일치하는 노드를 포함하는 [XPathNavigator](../) 객체이며, 쿼리 결과가 없을 경우 **nullptr**를 반환합니다.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) 메서드

[XPathNavigator](../)에서 지정된 [XPathExpression](../../xpathexpression/) 객체를 사용하여 단일 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | [XPathExpression](../../xpathexpression/) 객체는 컴파일된 [XPath](../../) 쿼리를 포함합니다. |

### 반환 값

지정된 [XPath](../../) 쿼리에 대해 첫 번째 일치하는 노드를 포함하는 [XPathNavigator](../) 객체이며, 쿼리 결과가 없을 경우 **nullptr**를 반환합니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 클래스 [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* 클래스 [XPathExpression](../../xpathexpression/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)