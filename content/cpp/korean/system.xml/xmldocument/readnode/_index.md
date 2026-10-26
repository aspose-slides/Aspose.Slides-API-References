---
title: ReadNode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlReader의 정보를 기반으로 XmlNode 객체를 생성합니다. 리더는 노드 또는 속성에 위치해야 합니다.
type: docs
weight: 495
url: /ko/system.xml/xmldocument/readnode/
---
## XmlDocument::ReadNode(SharedPtr\<XmlReader\>) 메서드


[XmlReader](../../xmlreader/)의 정보를 기반으로 [XmlNode](../../xmlnode/) 객체를 생성합니다. 리더는 노드 또는 속성에 위치해야 합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::ReadNode(SharedPtr<XmlReader> reader)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | XML 소스. |

### 반환값

새로운 [XmlNode](../../xmlnode/) 또는 더 이상 노드가 없을 경우 **nullptr**.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlReader](../../xmlreader/)
* 클래스 [XmlDocument](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)