---
title: InsertAfter()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 노드를 지정된 기준 노드 바로 뒤에 삽입합니다.
type: docs
weight: 222
url: /ko/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) 메서드

지정된 노드를 지정된 기준 노드 바로 뒤에 삽입합니다.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | 삽입할 [XmlNode](../../xmlnode/). |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | [XmlNode](../../xmlnode/)(은/는) 기준 노드입니다. **newChild**는 **refChild** 뒤에 배치됩니다. |

### 반환 값

삽입된 [XmlNode](../../xmlnode/).

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlAttribute](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)