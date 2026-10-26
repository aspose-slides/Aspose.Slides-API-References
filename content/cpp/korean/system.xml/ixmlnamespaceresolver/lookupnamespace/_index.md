---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 접두사에 매핑된 네임스페이스 URI를 반환합니다.
type: docs
weight: 14
url: /ko/system.xml/ixmlnamespaceresolver/lookupnamespace/
---
## IXmlNamespaceResolver::LookupNamespace(const String\&) 메서드

지정된 접두사에 매핑된 네임스페이스 URI를 반환합니다.

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupNamespace(const String &prefix)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | 네임스페이스 URI를 찾고자 하는 접두사. |

### 반환값

접두사에 매핑된 네임스페이스 URI; 접두사가 네임스페이스 URI에 매핑되지 않은 경우 **nullptr**.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [IXmlNamespaceResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)