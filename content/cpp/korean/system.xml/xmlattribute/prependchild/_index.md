---
title: PrependChild()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 노드를 이 노드의 자식 노드 목록 앞에 추가합니다.
type: docs
weight: 261
url: /ko/system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) method


지정된 노드를 이 노드의 자식 노드 목록 앞에 추가합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 추가할 [XmlNode](../../xmlnode/). [XmlDocumentFragment](../../xmldocumentfragment/)인 경우, 문서 조각의 전체 내용이 이 노드의 자식 목록으로 이동됩니다. |

### 반환값

추가된 [XmlNode](../../xmlnode/).

## 또보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlAttribute](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)