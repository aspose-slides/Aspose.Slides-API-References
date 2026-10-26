---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 접두사에 대한 네임스페이스 URI를 반환합니다.
type: docs
weight: 118
url: /ko/system.xml/xmlnamespacemanager/lookupnamespace/
---
## XmlNamespaceManager::LookupNamespace(const String\&) 메서드

지정된 접두사에 대한 네임스페이스 URI를 반환합니다.

```cpp
String System::Xml::XmlNamespaceManager::LookupNamespace(const String &prefix) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 해결하려는 네임스페이스 URI를 가진 접두사입니다. 기본 네임스페이스와 일치시키려면 [String::Empty](../../../system/string/empty/)을(를) 전달하십시오. |

### 반환 값

**prefix**에 대한 네임스페이스 URI 또는 매핑된 네임스페이스가 없을 경우 **nullptr**을 반환합니다. 반환된 문자열은 원자화됩니다. 원자화된 문자열에 대한 자세한 내용은 [XmlNameTable](../../xmlnametable/) 클래스를 참조하십시오.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamespaceManager](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)