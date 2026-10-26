---
title: WriteNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, reader에서 writer로 모든 내용을 복사하고 reader를 다음 형제 요소의 시작으로 이동합니다.
type: docs
weight: 430
url: /ko/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) 메서드


파생 클래스에서 재정의될 경우, reader에서 writer로 모든 내용을 복사하고 reader를 다음 형제 요소의 시작으로 이동합니다.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/)를 읽기 위해. |
| defattr | **bool** | **true**는 [XmlReader](../../xmlreader/)에서 기본 속성을 복사합니다; 그렇지 않으면 **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) 메서드


XPathNavigator 객체에서 writer로 모든 내용을 복사합니다. XPathNavigator의 위치는 변경되지 않습니다.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | 복사할 XPathNavigator. |
| defattr | **bool** | **true**는 기본 속성을 복사합니다; 그렇지 않으면 **false**. |

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlReader](../../xmlreader/)
* 클래스 [XmlWriter](../)
* 클래스 [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)