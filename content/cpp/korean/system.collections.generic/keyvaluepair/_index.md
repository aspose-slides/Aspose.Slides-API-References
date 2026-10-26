---
title: KeyValuePair
second_title: Aspose.Slides for C++ API 참조
description: "키와 값의 쌍입니다. 이 유형은 스택에 할당하고 값을 복사하거나 참조로 함수를 통해 전달해야 합니다. 절대 System::SmartPtr 클래스를 사용하여 이 유형의 객체를 관리하지 마세요."
type: docs
weight: 378
url: /ko/system.collections.generic/keyvaluepair/
---
## KeyValuePair 클래스

키와 값의 쌍입니다. 이 유형은 스택에 할당하고 값을 복사하거나 참조로 함수를 통해 전달해야 합니다. 절대 [System::SmartPtr](../../system/smartptr/) 클래스를 사용하여 이 유형의 객체를 관리하지 마세요.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | 키를 가져옵니다. |
| const TValue\& [get_Value](./get_value/)() const | 값을 가져옵니다. |
| int [GetHashCode](./gethashcode/)() const | 키와 값의 해시를 XOR하여 키-값 쌍의 해시를 계산합니다. |
| **bool** [IsNull](./isnull/)() const | 항상 false를 반환합니다. |
|  [KeyValuePair](./keyvaluepair/)() | 널 키-값 쌍 초기화기. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | 생성자. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | 형 변환 생성자. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | IComparer<KeyValuePair<TKey, TValue>>에서 상속된 클래스용 패치이며, 아무것도 비교하지 않습니다. |
| [String](../../system/string/) [ToString](./tostring/)() const | 키-값 쌍을 문자열로 변환합니다. |

## 참고

* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)