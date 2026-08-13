---
title: operator!=()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 역방향 'equals' 의미를 사용하여 두 키-값 쌍을 비교합니다.
type: docs
weight: 703
url: /ko/system.collections.generic/operator_not_equal/
---
## System::Collections::Generic::operator!=(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 함수

두 키-값 쌍을 역 'equals' 의미를 사용하여 비교합니다.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator!=(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키 유형. |
| TValue | 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 좌항 피연산자. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 우항 피연산자. |

### 반환값

키와 값이 모두 일치하지 않으면 true, 그렇지 않으면 false.

## 또보기

* 클래스 [KeyValuePair](../keyvaluepair/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)