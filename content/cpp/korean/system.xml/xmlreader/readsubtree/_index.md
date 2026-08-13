---
title: ReadSubtree()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드와 그 모든 하위 노드를 읽는 데 사용할 수 있는 새로운 XmlReader 인스턴스를 반환합니다.
type: docs
weight: 963
url: /ko/system.xml/xmlreader/readsubtree/
---
## XmlReader::ReadSubtree() 메서드

현재 노드와 그 모든 하위 노드를 읽는 데 사용할 수 있는 새로운 [XmlReader](../) 인스턴스를 반환합니다.

```cpp
virtual SharedPtr<XmlReader> System::Xml::XmlReader::ReadSubtree()
```

### 반환 값

새로운 XML 리더 인스턴스가 [ReadState::Initial](../../readstate/) 로 설정됩니다. [XmlReader::Read](../read/) 메서드를 호출하면 새 리더가 [XmlReader::ReadSubtree](./) 메서드를 호출하기 전에 현재였던 노드에 위치합니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* Library [Aspose.Slides](../../../)