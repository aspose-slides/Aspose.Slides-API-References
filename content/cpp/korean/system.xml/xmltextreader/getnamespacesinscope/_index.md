---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 범위에 있는 모든 네임스페이스를 포함하는 컬렉션을 반환합니다.
type: docs
weight: 716
url: /ko/system.xml/xmltextreader/getnamespacesinscope/
---
## XmlTextReader::GetNamespacesInScope(XmlNamespaceScope) 메서드

현재 범위에 있는 모든 네임스페이스를 포함하는 컬렉션을 반환합니다.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlTextReader::GetNamespacesInScope(XmlNamespaceScope scope) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | XmlNamespaceScope 값으로, 반환할 네임스페이스 노드의 유형을 지정합니다. |

### 반환값

현재 범위에 있는 모든 네임스페이스를 포함하는 IDictionary 객체입니다. 읽기기가 요소에 위치하지 않은 경우, 빈 사전(네임스페이스 없음)이 반환됩니다.

## 참조

* 열거형 [XmlNamespaceScope](../../xmlnamespacescope/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlTextReader](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)