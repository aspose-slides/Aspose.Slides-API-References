---
title: LookupPrefix()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 네임스페이스 URI에 매핑된 접두사를 반환합니다.
type: docs
weight: 27
url: /ko/system.xml/ixmlnamespaceresolver/lookupprefix/
---
## IXmlNamespaceResolver::LookupPrefix(const String\&) 메서드


지정된 네임스페이스 URI에 매핑된 접두사를 반환합니다.

```cpp
virtual String System::Xml::IXmlNamespaceResolver::LookupPrefix(const String &namespaceName)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| namespaceName | const [String](../../../system/string/)\& | 접두사를 찾고자 하는 네임스페이스 URI입니다. |

### 반환값

네임스페이스 URI에 매핑된 접두사이며, 네임스페이스 URI가 접두사에 매핑되지 않은 경우 **nullptr**를 반환합니다.

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IXmlNamespaceResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)