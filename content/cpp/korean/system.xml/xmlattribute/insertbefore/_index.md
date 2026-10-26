---
title: InsertBefore()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 노드를 지정된 기준 노드 바로 앞에 삽입합니다.
type: docs
weight: 209
url: /ko/system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 메서드

지정된 노드를 지정된 기준 노드 바로 앞에 삽입합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 삽입할 [XmlNode](../../xmlnode/). |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/)는 기준 노드입니다. **newChild**는 이 노드 앞에 배치됩니다. |

### 반환값

삽입된 [XmlNode](../../xmlnode/).

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlAttribute](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)