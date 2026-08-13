---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 배열의 요소들을 다른 유형으로 캐스팅합니다.
type: docs
weight: 2991
url: /ko/system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) 함수


지정된 배열의 요소들을 다른 유형으로 캐스팅합니다.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| To | 지정된 배열의 요소들을 캐스팅할 유형 |
| From | 캐스팅될 요소들의 유형 |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | 캐스팅할 요소들을 포함하는 배열에 대한 공유 포인터 |

### 반환값

새 배열에 대한 포인터로, **from**의 요소와 동일한 유형 **To**의 요소를 포함합니다.

더 이상 사용되지 않음
:   이전 호환성을 위해 추가되었습니다. 대신 ExplicitCast를 사용하십시오.

## 참조

* 타입 정의 [SharedPtr](../sharedptr/)
* 클래스 [Array](../array/)
* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)