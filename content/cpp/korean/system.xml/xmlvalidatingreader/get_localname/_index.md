---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 노드의 로컬 이름을 반환합니다.
type: docs
weight: 27
url: /ko/system.xml/xmlvalidatingreader/get_localname/
---
## XmlValidatingReader::get_LocalName() 메서드


현재 노드의 로컬 이름을 반환합니다.

```cpp
String System::Xml::XmlValidatingReader::get_LocalName() override
```


### 반환 값

접두사가 제거된 현재 노드의 이름입니다. 예를 들어, 요소 **<bk:book>**에 대해 **LocalName**은 **book**입니다. 이름이 없는 노드 유형(예: **[Text](../../../system.text/)**, **Comment** 등)에서는 이 메서드가 [String::Empty](../../../system/string/empty/)를 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlValidatingReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)