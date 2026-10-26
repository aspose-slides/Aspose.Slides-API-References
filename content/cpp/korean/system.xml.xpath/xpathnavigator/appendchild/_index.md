---
title: AppendChild()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 자식 노드 목록 끝에 하나 이상의 새로운 자식 노드를 만들 때 사용하는 XmlWriter 객체를 반환합니다.
type: docs
weight: 885
url: /ko/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() 메서드

현재 노드의 자식 노드 목록 끝에 하나 이상의 새로운 자식 노드를 만들 때 사용하는 [XmlWriter](../../../system.xml/xmlwriter/) 객체를 반환합니다.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### 반환값

현재 노드의 자식 노드 목록 끝에 새로운 자식 노드를 만들 때 사용하는 [XmlWriter](../../../system.xml/xmlwriter/) 객체.

## XPathNavigator::AppendChild(String) 메서드

지정된 XML 데이터 문자열을 사용하여 현재 노드의 자식 노드 목록 끝에 새로운 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 새로운 자식 노드에 대한 XML 데이터 문자열입니다. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체의 XML 콘텐츠를 사용하여 현재 노드의 자식 노드 목록 끝에 새로운 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 새로운 자식 노드에 대한 XML 데이터에 위치한 [XmlReader](../../../system.xml/xmlreader/) 객체입니다. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) 메서드

지정된 [XPathNavigator](../)에 있는 노드를 사용하여 현재 노드의 자식 노드 목록 끝에 새로운 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 새로운 자식 노드로 추가할 노드에 위치한 [XPathNavigator](../) 객체입니다. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)