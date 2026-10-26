---
title: GetMember()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 이름을 가진 멤버들의 목록을 가져옵니다.
type: docs
weight: 495
url: /ko/system/typeinfo/getmember/
---
## TypeInfo::GetMember(const String\&) const method


지정된 이름을 가진 멤버들의 목록을 가져옵니다.

```cpp
ArrayPtr<SharedPtr<System::Reflection::MemberInfo>> System::TypeInfo::GetMember(const String &name) const
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | const [String](../../string/)\& | 가져올 멤버의 이름. |

### 반환 값

[Array](../../array/) 멤버 설명자 (멤버를 찾지 못한 경우 비어 있음).

## 또 보기

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [MemberInfo](../../../system.reflection/memberinfo/)
* 클래스 [String](../../string/)
* 클래스 [TypeInfo](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)