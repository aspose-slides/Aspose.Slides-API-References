---
title: PrependChild()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 자식 노드 목록 앞에 새 자식 노드를 만들 때 사용되는 XmlWriter 객체를 반환합니다.
type: docs
weight: 872
url: /ko/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() 메서드

현재 노드의 자식 노드 목록 앞에 새 자식 노드를 만들 때 사용되는 [XmlWriter](../../../system.xml/xmlwriter/) 객체를 반환합니다.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### 반환값

현재 노드의 자식 노드 목록 앞에 새 자식 노드를 만들 때 사용되는 [XmlWriter](../../../system.xml/xmlwriter/) 객체를 반환합니다.

## XPathNavigator::PrependChild(String) 메서드

지정된 XML 문자열을 사용하여 현재 노드의 자식 노드 목록 앞에 새 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | 새 자식 노드에 대한 XML 데이터 문자열. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체의 XML 내용을 사용하여 현재 노드의 자식 노드 목록 앞에 새 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | [XmlReader](../../../system.xml/xmlreader/) 객체는 새 자식 노드의 XML 데이터에 위치합니다. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) 메서드

지정된 [XPathNavigator](../) 객체의 노드를 사용하여 현재 노드의 자식 노드 목록 앞에 새 자식 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) 객체는 새 자식 노드로 추가할 노드에 위치합니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 네임스페이스 [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)