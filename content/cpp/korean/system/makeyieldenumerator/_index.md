---
title: MakeYieldEnumerator()
second_title: C++용 Aspose.Slides API 레퍼런스
description: yield 함수에서 IEnumerator를 생성합니다.
type: docs
weight: 2432
url: /ko/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) 함수

yield 함수에서 IEnumerator를 생성합니다.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| T | 시퀀스에 있는 요소의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | 실행할 yield 함수 |

## 반환값

IEnumerator에 대한 공유 포인터

## 관련 내용

* typedef [SharedPtr](../sharedptr/)
* 클래스 [IEnumerator](../../system.collections.generic/ienumerator/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)