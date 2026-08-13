---
title: IEnumerableToStr()
second_title: Aspose.Slides for C++ API 참조
description: 요소들의 문자열 표현을 결합하여 컬렉션을 문자열로 변환합니다.
type: docs
weight: 40
url: /ko/system/collectionasserthelper/ienumerabletostr/
---
## CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T\>\>\&) 메서드

요소들의 문자열 표현을 결합하여 컬렉션을 문자열로 변환합니다.

```cpp
template<typename T> static System::String System::CollectionAssertHelper::IEnumerableToStr(const System::SharedPtr<System::Collections::Generic::IEnumerable<T>> &ie)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 컬렉션 요소 타입. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ie | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T\>\>\& | 검사할 컬렉션. |

### 반환 값

컬렉션의 결합된 값.

## 관련 항목

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)