---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 네임스페이스 URI에 대해 선언된 접두사를 반환합니다.
type: docs
weight: 417
url: /ko/system.xml.xpath/xpathnavigator/lookupprefix/
---
## XPathNavigator::LookupPrefix(const String\&) 메서드

지정된 네임스페이스 URI에 대해 선언된 접두사를 반환합니다.

```cpp
String System::Xml::XPath::XPathNavigator::LookupPrefix(const String &namespaceURI) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceURI | const [String](../../../system/string/)\& | 접두사를 확인하기 위한 네임스페이스 URI입니다. |

### 반환값

지정된 네임스페이스 URI에 할당된 네임스페이스 접두사를 포함하는 [String](../../../system/string/)이며, 네임스페이스 URI에 접두사가 할당되지 않은 경우 [String::Empty](../../../system/string/empty/)입니다. 반환된 [String](../../../system/string/)는 원자화됩니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XPathNavigator](../)
* 네임스페이스 [System::Xml::XPath](../../)
* 라이브러리 [Aspose.Slides](../../../)