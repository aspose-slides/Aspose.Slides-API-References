---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 선택된 노드 앞에 새로운 형제 노드를 만들기 위해 사용되는 XmlWriter 객체를 반환합니다.
type: docs
weight: 911
url: /ko/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() 메서드

현재 선택된 노드 앞에 새로운 형제 노드를 만들기 위해 사용되는 [XmlWriter](../../../system.xml/xmlwriter/) 객체를 반환합니다.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### 반환값

현재 선택된 노드 앞에 새로운 형제 노드를 만들기 위해 사용되는 [XmlWriter](../../../system.xml/xmlwriter/) 객체입니다.

## XPathNavigator::InsertBefore(String) 메서드

지정된 XML 문자열을 사용하여 현재 선택된 노드 앞에 새로운 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 새 형제 노드에 대한 XML 데이터 문자열. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 선택된 노드 앞에 새로운 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 새 형제 노드에 대한 XML 데이터에 위치한 [XmlReader](../../../system.xml/xmlreader/) 객체. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) 메서드

지정된 [XPathNavigator](../)에 있는 노드를 사용하여 현재 선택된 노드 앞에 새로운 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 새 형제 노드로 추가할 노드에 위치한 [XPathNavigator](../) 객체. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)