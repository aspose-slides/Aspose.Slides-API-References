---
title: With()
second_title: Aspose.Slides C++ API 레퍼런스
description: 레코드 참조를 복제하고 초기화 functor를 적용합니다.
type: docs
weight: 2614
url: /ko/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) function

레코드 참조를 복제하고 초기화 functor를 적용합니다.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 복제할 레코드 유형. |
| A | 초기화 functor 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | 복제하고 초기화할 객체에 대한 공유 포인터. |
| initializer | const A\& | 레코드 복제본에 적용되는 초기화 functor. |

### 반환값

복제된 레코드에 대한 공유 포인터.

## System::With(const T\&, const A\&) function

구조체 레코드를 복사하고 초기화 functor를 적용합니다.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 복사할 레코드 유형. |
| A | 초기화 functor 유형. |

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| record | const T\& | 복사하고 초기화할 레코드. |
| initializer | const A\& | 레코드 복사본에 적용되는 초기화 functor. |

### 반환값

복사된 레코드.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)