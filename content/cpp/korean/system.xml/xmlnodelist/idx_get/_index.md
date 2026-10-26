---
title: idx_get()
second_title: Aspose.Slides for C++ API 참조
description: 주어진 인덱스에 해당하는 노드를 반환합니다.
type: docs
weight: 40
url: /ko/system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) 메서드


주어진 인덱스에 해당하는 노드를 반환합니다.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| i | **int32_t** | 노드 목록에 대한 0부터 시작하는 인덱스입니다. |

### 반환값

컬렉션에서 지정된 인덱스에 해당하는 [XmlNode](../../xmlnode/)입니다. 인덱스가 목록에 있는 노드 수보다 크거나 같으면 **nullptr**를 반환합니다.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlNode](../../xmlnode/)
* 클래스 [XmlNodeList](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)