---
title: Item()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 주어진 인덱스에 해당하는 노드를 반환합니다.
type: docs
weight: 14
url: /ko/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(int32_t) 메서드


주어진 인덱스에 해당하는 노드를 반환합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 노드 목록에 대한 0 기반 인덱스. |

### 반환값

컬렉션에서 지정된 인덱스를 가진 [XmlNode](../../xmlnode/). **index**가 목록에 있는 노드 수보다 크거나 같으면, **nullptr**를 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNodeList](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)