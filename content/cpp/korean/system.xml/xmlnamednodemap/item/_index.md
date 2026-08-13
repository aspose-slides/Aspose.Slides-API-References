---
title: Item()
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlNamedNodeMap에서 지정된 인덱스에 있는 노드를 검색합니다.
type: docs
weight: 53
url: /ko/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(int32_t) 메서드

지정된 인덱스에 있는 노드를 [XmlNamedNodeMap](../)에서 검색합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | [XmlNamedNodeMap](../)에서 검색할 노드의 인덱스 위치입니다. 인덱스는 0부터 시작하므로 첫 번째 노드의 인덱스는 0이고 마지막 노드의 인덱스는 [XmlNamedNodeMap::get_Count](../get_count/) - 1입니다. |

### 반환값

지정된 인덱스에 있는 [XmlNode](../../xmlnode/)입니다. **index**가 0보다 작거나 [XmlNamedNodeMap::get_Count](../get_count/) 값보다 크거나 같으면 **nullptr**가 반환됩니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNamedNodeMap](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)