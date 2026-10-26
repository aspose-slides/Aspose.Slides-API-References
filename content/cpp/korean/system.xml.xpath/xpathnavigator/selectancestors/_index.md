---
title: SelectAncestors()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드와 일치하는 XPathNodeType을 가진 모든 조상 노드를 선택합니다.
type: docs
weight: 846
url: /ko/system.xml.xpath/xpathnavigator/selectancestors/
---
## XPathNavigator::SelectAncestors(XPathNodeType, bool) 메서드

현재 노드의 조상 노드 중 XPathNodeType이 일치하는 모든 조상 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(XPathNodeType type, bool matchSelf)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 조상 노드의 XPathNodeType. |
| matchSelf | **bool** | 선택에 현재 컨텍스트 노드를 포함하려면 **true**; 그렇지 않으면 **false**. |

### 반환값

[XPathNodeIterator](../../xpathnodeiterator/)는 선택된 노드를 포함합니다. 반환된 노드는 역문서 순서로 정렬됩니다.

## XPathNavigator::SelectAncestors(String, String, bool) 메서드

현재 노드의 조상 노드 중 지정된 로컬 이름과 네임스페이스 URI를 가진 모든 조상 노드를 선택합니다.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::SelectAncestors(String name, String namespaceURI, bool matchSelf)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [String](../../../system/string/) | 조상 노드의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 조상 노드의 네임스페이스 URI. |
| matchSelf | **bool** | 선택에 현재 컨텍스트 노드를 포함하려면 **true**; 그렇지 않으면 **false**. |

### 반환값

[XPathNodeIterator](../../xpathnodeiterator/)는 선택된 노드를 포함합니다. 반환된 노드는 역문서 순서로 정렬됩니다.

## 관련 항목

* 열거형 [XPathNodeType](../../xpathnodetype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XPathNodeIterator](../../xpathnodeiterator/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)