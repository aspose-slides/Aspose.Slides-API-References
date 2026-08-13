---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 튜플 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system/tuplefactory/create/
---
## TupleFactory::Create(Args...) 메서드

새 튜플 객체를 생성합니다.

```cpp
template<typename ...> static SharedPtr<Tuple<Args...>> System::TupleFactory::Create(Args... args)
```

## TupleFactory::Create(T1, T2, T3, T4, T5, T6, T7, TRest) 메서드

새 8-튜플을 생성합니다. 8번째 요소는 [Tuple](../../tuple/) 내부에 저장됩니다.

```cpp
template<typename T1,typename T2,typename T3,typename T4,typename T5,typename T6,typename T7,typename TRest> static SharedPtr<Tuple<T1, T2, T3, T4, T5, T6, T7, SharedPtr<Tuple<TRest>>>> System::TupleFactory::Create(T1 item1, T2 item2, T3 item3, T4 item4, T5 item5, T6 item6, T7 item7, TRest rest)
```

## 참조

* 타입 정의 [SharedPtr](../../sharedptr/)
* 클래스 [Tuple](../../tuple/)
* 클래스 [TupleFactory](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)