---
title: get_BaseURI()
second_title: Aspose.Slides for C++ API 참조
description: 노드의 기본 Uniform Resource Identifier (URI)를 반환합니다.
type: docs
weight: 183
url: /ko/system.xml/xmlattribute/get_baseuri/
---
## XmlAttribute::get_BaseURI() 메서드

노드의 기본 Uniform Resource Identifier (URI)를 반환합니다.

```cpp
String System::Xml::XmlAttribute::get_BaseURI() override
```

### 반환 값

노드가 로드된 위치이며, 노드에 기본 URI가 없는 경우 [String::Empty](../../../system/string/empty/)을 반환합니다. [Attribute](../../../system/attribute/) 노드는 소유 요소와 동일한 기본 URI를 가집니다. 속성 노드에 소유 요소가 없으면 get_BaseURI는 [String::Empty](../../../system/string/empty/)을 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlAttribute](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)