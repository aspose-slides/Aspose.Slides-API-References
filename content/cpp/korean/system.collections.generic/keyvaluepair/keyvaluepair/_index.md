---
title: KeyValuePair()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 널 키-값 쌍 초기화기.
type: docs
weight: 1
url: /ko/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() 생성자

키-값 쌍 초기화기.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) 생성자

생성자.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const TKey\& | 키. |
| value | const TValue\& | 값. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) 생성자

형 변환 생성자.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| OtherK | 다른 키 유형. |
| OtherV | 다른 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | 쌍 값. |

## 참조

* 클래스 [KeyValuePair](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)