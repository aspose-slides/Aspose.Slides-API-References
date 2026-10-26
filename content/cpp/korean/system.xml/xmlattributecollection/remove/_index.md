---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 지정된 속성을 제거합니다.
type: docs
weight: 79
url: /ko/system.xml/xmlattributecollection/remove/
---
## XmlAttributeCollection::Remove(const SharedPtr\<XmlAttribute\>\&) method


지정된 속성을 컬렉션에서 제거합니다.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlAttributeCollection::Remove(const SharedPtr<XmlAttribute> &node)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| node | const [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\>\& | 제거할 속성. |

### 반환값

제거된 node이며, 컬렉션에서 찾지 못하면 **nullptr**를 반환합니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlAttribute](../../xmlattribute/)
* Class [XmlAttributeCollection](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)