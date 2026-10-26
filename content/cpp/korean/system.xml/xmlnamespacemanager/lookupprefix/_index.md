---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 주어진 네임스페이스 URI에 대해 선언된 접두사를 찾습니다.
type: docs
weight: 131
url: /ko/system.xml/xmlnamespacemanager/lookupprefix/
---
## XmlNamespaceManager::LookupPrefix(const String\&) method

지정된 네임스페이스 URI에 대해 선언된 접두사를 찾습니다.

```cpp
String System::Xml::XmlNamespaceManager::LookupPrefix(const String &uri) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | const [String](../../../system/string/)\& | 접두사를 확인할 네임스페이스입니다. |

### 반환값

일치하는 접두사입니다. 매핑된 접두사가 없으면 메서드는 [String::Empty](../../../system/string/empty/)을 반환합니다. null 값이 제공되면 **nullptr**가 반환됩니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamespaceManager](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)