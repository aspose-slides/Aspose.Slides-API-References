---
title: get_DeclaredMember()
second_title: Aspose.Slides C++용 API 참조
description: 지정된 이름을 가진 멤버들의 목록을 가져옵니다.
type: docs
weight: 508
url: /ko/system/typeinfo/get_declaredmember/
---
## TypeInfo::get_DeclaredMember(const String\&) const method

지정된 이름을 가진 멤버들의 목록을 가져옵니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::get_DeclaredMember(const String &name) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 가져올 멤버의 이름. |

### 반환값

[Array](../../array/) 멤버 설명자(멤버를 찾지 못하면 비어 있습니다).

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [MemberInfo](../../../system.reflection/memberinfo/)
* 클래스 [String](../../string/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)