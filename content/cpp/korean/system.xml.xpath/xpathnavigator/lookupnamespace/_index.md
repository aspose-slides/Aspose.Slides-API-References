---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 접두사에 대한 네임스페이스 URI를 반환합니다.
type: docs
weight: 404
url: /ko/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) 메서드

지정된 접두사에 대한 네임스페이스 URI를 반환합니다.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 해결하려는 네임스페이스 URI의 접두사입니다. 기본 네임스페이스와 일치시키려면 [String::Empty](../../../system/string/empty/)를 전달하십시오. |

### 반환값

지정된 네임스페이스 접두사에 할당된 네임스페이스 URI를 포함하는 [String](../../../system/string/)입니다; 접두사에 네임스페이스 URI가 할당되지 않은 경우 **nullptr**를 반환합니다. 반환된 [String](../../../system/string/)는 원자화됩니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)