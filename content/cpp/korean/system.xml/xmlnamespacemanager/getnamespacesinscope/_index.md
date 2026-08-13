---
title: GetNamespacesInScope()
second_title: Aspose.Slides for C++ API 참조
description: 현재 범위에 있는 네임스페이스를 열거하는 데 사용할 수 있는, 접두사별로 키가 지정된 네임스페이스 이름 컬렉션을 반환합니다.
type: docs
weight: 105
url: /ko/system.xml/xmlnamespacemanager/getnamespacesinscope/
---
## XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope) 메서드


현재 범위에 있는 네임스페이스를 열거하는 데 사용할 수 있는, 접두사별로 키가 지정된 네임스페이스 이름 컬렉션을 반환합니다.

```cpp
SharedPtr<Collections::Generic::IDictionary<String, String>> System::Xml::XmlNamespaceManager::GetNamespacesInScope(XmlNamespaceScope scope) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scope | [XmlNamespaceScope](../../xmlnamespacescope/) | 반환할 네임스페이스 노드 유형을 지정하는 열거값입니다. |

### 반환값

현재 범위에 있는 네임스페이스와 접두사 쌍의 컬렉션입니다.

## 관련 항목

* 열거형 [XmlNamespaceScope](../../xmlnamespacescope/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IDictionary](../../../system.collections.generic/idictionary/)
* 클래스 [String](../../../system/string/)
* 클래스 [XmlNamespaceManager](../)
* 네임스페이스 [System::Xml](../../)
* 라이브러리 [Aspose.Slides](../../../)