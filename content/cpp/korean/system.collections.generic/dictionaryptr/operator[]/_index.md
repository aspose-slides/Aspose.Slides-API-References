---
title: operator[]()
second_title: Aspose.Slides C++ API 레퍼런스
description: 키 유형 변환을 수행하는 액세스 연산자입니다.
type: docs
weight: 14
url: /ko/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const 메서드

키 유형 변환을 수행하는 액세스 연산자입니다.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| X | 원본 키 유형. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) 키. |

### 반환값

전달된 키에 해당하는 값에 대한 참조이며, 기존이거나 새로 생성된 값입니다.

## DictionaryPtr::operator[](const T\&) const 메서드

액세스 연산자입니다.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) 키. |

### 반환값

전달된 키에 해당하는 값에 대한 참조이며, 기존이거나 새로 생성된 값입니다.

## 관련 항목

* 클래스 [DictionaryPtr](../)
* 네임스페이스 [System::Collections::Generic](../../)
* 라이브러리 [Aspose.Slides](../../../)