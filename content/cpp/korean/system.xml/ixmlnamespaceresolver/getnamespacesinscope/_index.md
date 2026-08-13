---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 참조
description: 현재 범위에 있는 정의된 접두사-네임스페이스 매핑 컬렉션을 반환합니다.
type: docs
weight: 1
url: /ko/system.xml/ixmlnamespaceresolver/getnamespacesinscope/
---
## IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope) 메서드

현재 범위에 있는 정의된 접두사-네임스페이스 매핑 컬렉션을 반환합니다.

```cpp
virtual SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::IXmlNamespaceResolver::GetNamespacesInScope(XmlNamespaceScope scope)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 반환할 네임스페이스 노드의 유형을 지정하는 XmlNamespaceScope 값. |

### 반환 값

현재 범위에 있는 네임스페이스를 포함하는 IDictionary 컬렉션.

## 참고

* 열거형 [XmlNamespaceScope](../../xmlnamespacescope/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [IXmlNamespaceResolver](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)