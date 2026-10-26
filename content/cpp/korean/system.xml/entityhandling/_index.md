---
title: EntityHandling
second_title: Aspose.Slides for C++ API 레퍼런스
description: XmlTextReader 또는 XmlValidatingReader가 엔터티를 처리하는 방식을 지정합니다.
type: docs
weight: 651
url: /ko/system.xml/entityhandling/
---
## EntityHandling 열거형

[XmlTextReader](../xmltextreader/) 또는 [XmlValidatingReader](../xmlvalidatingreader/)가 엔터티를 처리하는 방식을 지정합니다.

```cpp
enum class EntityHandling
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| ExpandEntities | 1 | 모든 엔터티를 확장하고 확장된 노드를 반환합니다. |
| ExpandCharEntities | 2 | 문자 엔터티를 확장하고 일반 엔터티를 [XmlNodeType::EntityReference](../xmlnodetype/) 노드로 반환합니다. |

## 참조

* 네임스페이스 [System::Xml](../)
* 라이브러리 [Aspose.Slides](../../)