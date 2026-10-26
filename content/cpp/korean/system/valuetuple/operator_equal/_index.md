---
title: operator=()
second_title: Aspose.Slides for C++ API 참조
description: 
type: docs
weight: 92
url: /ko/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) 메서드




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) 메서드

객체를 이 값 튜플로 분해합니다.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | 분해할 객체 |

## 참고

* 타입정의 [SharedPtr](../../sharedptr/)
* 클래스 [ValueTuple](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)