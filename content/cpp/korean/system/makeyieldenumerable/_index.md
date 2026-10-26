---
title: MakeYieldEnumerable()
second_title: Aspose.Slides for C++ API 참조
description: yield 함수에서 IEnumerable을 생성합니다.
type: docs
weight: 2419
url: /ko/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) function

Creates an IEnumerable from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 시퀀스에 포함된 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 실행할 yield 함수 |

### 반환값

IEnumerable에 대한 공유 포인터

## 참조

* 타입정의 [SharedPtr](../sharedptr/)
* 클래스 [IEnumerable](../../system.collections.generic/ienumerable/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)