---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 메시지 표현을 위해 두 컬렉션을 직렬화합니다.
type: docs
weight: 53
url: /ko/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) 메서드

두 컬렉션을 메시지 표현을 위해 직렬화합니다.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T1 | 예상 컬렉션 요소 유형. |
| T2 | 실제 컬렉션 요소 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | 결과 메시지에서 예상값 앞에 삽입되는 사용자 지정 문자열 |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | 예상 컬렉션. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | 실제 컬렉션. |

### 반환 값

컬렉션 내용에 대한 사용자 친화적인 메시지.

## 또 보기

* Typedef [SharedPtr](../../sharedptr/)
* 클래스 [String](../../string/)
* 클래스 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 구조체 [CollectionAssertHelper](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)