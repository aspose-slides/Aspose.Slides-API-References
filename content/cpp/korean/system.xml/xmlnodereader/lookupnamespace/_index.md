---
title: LookupNamespace()
second_title: C++용 Aspose.Slides API 참조
description: 현재 요소 범위에서 네임스페이스 접두사를 해결합니다.
type: docs
weight: 404
url: /ko/system.xml/xmlnodereader/lookupnamespace/
---
## XmlNodeReader::LookupNamespace(const String\&) 메서드

현재 요소 범위에서 네임스페이스 접두사를 해결합니다.

```cpp
String System::Xml::XmlNodeReader::LookupNamespace(const String &prefix) override
```

### Arguments

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 해결하려는 네임스페이스 URI를 가진 접두사입니다. 기본 네임스페이스와 일치시키려면 빈 문자열을 전달하십시오. 이 문자열은 원자화될 필요가 없습니다. |

### 반환 값

접두사가 매핑되는 네임스페이스 URI 또는 일치하는 접두사가 없을 경우 **nullptr**.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [XmlNodeReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)