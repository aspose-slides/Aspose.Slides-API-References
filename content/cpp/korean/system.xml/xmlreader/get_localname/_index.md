---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 파생 클래스에서 재정의될 경우, 현재 노드의 로컬 이름을 가져옵니다.
type: docs
weight: 40
url: /ko/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() 메서드

파생 클래스에서 재정의될 경우, 현재 노드의 로컬 이름을 가져옵니다.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```

### 반환값

접두사가 제거된 현재 노드의 이름입니다. 예를 들어, **LocalName**은 요소 **<bk:book>**에 대해 **book**입니다. 이름이 없는 노드 유형(예: **[Text](../../../system.text/)**, **Comment** 등)의 경우, 이 메서드는 [String::Empty](../../../system/string/empty/)을 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)