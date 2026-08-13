---
title: operator<<()
second_title: C++용 Aspose.Slides API 참조
description: UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다.
type: docs
weight: 716
url: /ko/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) function

UTF-8 인코딩을 사용하여 스트림에 데이터를 삽입합니다.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키 유형. |
| TValue | 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | std::ostream\& | 데이터를 삽입할 출력 스트림. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) 삽입용. |

### 반환값

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) function

스트림에 데이터를 삽입합니다.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| TKey | 키 유형. |
| TValue | 값 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | std::wostream\& | 데이터를 삽입할 출력 스트림. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) 삽입용. |

### 반환값

**stream**.

## 참고

* 클래스 [KeyValuePair](../keyvaluepair/)
* 네임스페이스 [System::Collections::Generic](../)
* 라이브러리 [Aspose.Slides](../../)