---
title: ReplaceSelf()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 문자열의 내용으로 현재 노드를 교체합니다.
type: docs
weight: 950
url: /ko/system.xml.xpath/xpathnavigator/replaceself/
---
## XPathNavigator::ReplaceSelf(String) 메서드

지정된 문자열의 내용으로 현재 노드를 교체합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(String newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | [String](../../../system/string/) | 새로운 노드에 대한 XML 데이터 문자열입니다. |

## XPathNavigator::ReplaceSelf(SharedPtr\<XmlReader\>) 메서드

지정된 [XmlReader](../../../system.xml/xmlreader/) 객체의 내용으로 현재 노드를 교체합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XmlReader> newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | 새로운 노드에 대한 XML 데이터가 위치한 [XmlReader](../../../system.xml/xmlreader/) 객체입니다. |

## XPathNavigator::ReplaceSelf(SharedPtr\<XPathNavigator\>) 메서드

지정된 [XPathNavigator](../) 객체의 내용으로 현재 노드를 교체합니다.

```cpp
virtual void System::Xml::XPath::XPathNavigator::ReplaceSelf(SharedPtr<XPathNavigator> newNode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newNode | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | 새로운 노드에 위치한 [XPathNavigator](../) 객체입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)