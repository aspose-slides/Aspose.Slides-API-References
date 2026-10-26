---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 선택된 노드 뒤에 새 형제 노드를 만들 때 사용되는 XmlWriter 객체를 반환합니다.
type: docs
weight: 898
url: /ko/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() 메서드


현재 선택된 노드 뒤에 새 형제 노드를 만들 때 사용하는 [XmlWriter](../../../system.xml/xmlwriter/) 개체를 반환합니다.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```


### 반환 값

현재 선택된 노드 뒤에 새 형제 노드를 만들 때 사용하는 [XmlWriter](../../../system.xml/xmlwriter/) 개체입니다.

## XPathNavigator::InsertAfter(String) 메서드


지정된 XML 문자열을 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```


### 매개 변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | 새 형제 노드에 대한 XML 데이터 문자열입니다. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) 메서드


지정된 [XmlReader](../../../system.xml/xmlreader/) 개체의 XML 내용을 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```


### 매개 변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | [XmlReader](../../../system.xml/xmlreader/) 개체는 새 형제 노드의 XML 데이터에 위치합니다. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) 메서드


지정된 [XPathNavigator](../) 개체의 노드를 사용하여 현재 선택된 노드 뒤에 새 형제 노드를 생성합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```


### 매개 변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | [XPathNavigator](../) 개체는 새 형제 노드로 추가할 노드에 위치합니다. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlWriter](../../../system.xml/xmlwriter/)
* 클래스 [XPathNavigator](../)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../../../system.xml/xmlreader/)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)