---
title: MoveToFollowing()
second_title: Aspose.Slides for C++ API 참조
description: XPathNavigator를 문서 순서에 지정된 로컬 이름 및 네임스페이스 URI를 가진 요소로 이동시킵니다.
type: docs
weight: 703
url: /ko/system.xml.xpath/xpathnavigator/movetofollowing/
---
## XPathNavigator::MoveToFollowing(String, String) 메서드

[XPathNavigator](../)를 문서 순서에 지정된 로컬 이름 및 네임스페이스 URI를 가진 요소로 이동시킵니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 요소의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI. |

### 반환 값

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(String, String, SharedPtr\<XPathNavigator\>) 메서드

[XPathNavigator](../)를 문서 순서에 지정된 로컬 이름 및 네임스페이스 URI를 가진 요소로, 지정된 경계까지 이동시킵니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(String localName, String namespaceURI, SharedPtr<XPathNavigator> end)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localName | [String](../../../system/string/) | 요소의 로컬 이름. |
| namespaceURI | [String](../../../system/string/) | 요소의 네임스페이스 URI. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 다음 요소를 검색하는 동안 현재 [XPathNavigator](../)가 넘어가지 않을 요소 경계에 배치된 [XPathNavigator](../) 객체. |

### 반환 값

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType) 메서드

[XPathNavigator](../)를 문서 순서에 지정된 XPathNodeType의 다음 요소로 이동시킵니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 요소의 XPathNodeType. XPathNodeType은 [XPathNodeType::Attribute](../../xpathnodetype/) 또는 [XPathNodeType::Namespace](../../xpathnodetype/)일 수 없습니다. |

### 반환 값

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## XPathNavigator::MoveToFollowing(XPathNodeType, SharedPtr\<XPathNavigator\>) 메서드

[XPathNavigator](../)를 문서 순서에 지정된 XPathNodeType의 다음 요소로, 지정된 경계까지 이동시킵니다.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFollowing(XPathNodeType type, SharedPtr<XPathNavigator> end)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | 요소의 XPathNodeType. XPathNodeType은 [XPathNodeType::Attribute](../../xpathnodetype/) 또는 [XPathNodeType::Namespace](../../xpathnodetype/)일 수 없습니다. |
| end | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 다음 요소를 검색하는 동안 현재 [XPathNavigator](../)가 넘어가지 않을 요소 경계에 배치된 [XPathNavigator](../) 객체. |

### 반환 값

**true** if the [XPathNavigator](../) moved successfully; otherwise, **false**.

## 참고

* Enum [XPathNodeType](../../xpathnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)