---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 요소의 범위에서 네임스페이스 접두사를 해결합니다.
type: docs
weight: 547
url: /ko/system.xml/xmlvalidatingreader/lookupnamespace/
---
## XmlValidatingReader::LookupNamespace(const String\&) method

현재 요소의 범위에서 네임스페이스 접두사를 해결합니다.

```cpp
String System::Xml::XmlValidatingReader::LookupNamespace(const String &prefix) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 해결하려는 네임스페이스 Uniform Resource Identifier (URI)인 접두사입니다. 기본 네임스페이스와 일치시키려면 빈 문자열을 전달하십시오. |

### 반환 값

접두사가 매핑되는 네임스페이스 URI이며, 일치하는 접두사가 없으면 **nullptr**를 반환합니다.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [XmlValidatingReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)