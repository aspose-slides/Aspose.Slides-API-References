---
title: operator==()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "'equals' 의미론을 사용하여 두 키-값 쌍을 비교합니다. 정의된 경우 키와 값 모두에 대해 연산자 == 또는 EqualsTo 메서드를 사용합니다."
type: docs
weight: 690
url: /ko/system.collections.generic/operator_equal_equal/
---
## System::Collections::Generic::operator==(const KeyValuePair\<TKey, TValue\>\&, const KeyValuePair\<TKey, TValue\>\&) 함수

두 키-값 쌍을 'equals' 의미론을 사용하여 비교합니다. 정의된 경우 키와 값 모두에 대해 연산자 == 또는 EqualsTo 메서드를 사용합니다.

```cpp
template<typename TKey,typename TValue> bool System::Collections::Generic::operator==(const KeyValuePair<TKey, TValue> &left, const KeyValuePair<TKey, TValue> &right)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키 형식. |
| TValue | 값 형식. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| left | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 좌변 피연산자. |
| right | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | 우변 피연산자. |

### 반환 값

키와 값이 모두 일치하면 true, 그렇지 않으면 false.

## 참고

* 클래스 [KeyValuePair](../keyvaluepair/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)