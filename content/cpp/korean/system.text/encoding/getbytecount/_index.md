---
title: GetByteCount()
second_title: Aspose.Slides for C++ API 참조
description: 문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.
type: docs
weight: 235
url: /ko/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) 메서드


문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 문자 버퍼. |
| index | int | 슬라이스 시작. |
| count | int | 슬라이스 크기. |

### 반환 값

필요한 버퍼 크기.

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) 메서드


문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 문자 버퍼. |
| index | int | 슬라이스 시작. |
| count | int | 슬라이스 크기. |

### 반환 값

필요한 버퍼 크기.

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) 메서드


문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 문자 버퍼. |
| index | int | 슬라이스 시작. |
| count | int | 슬라이스 크기. |

### 반환 값

필요한 버퍼 크기.

## Encoding::GetByteCount(const String\&) 메서드


문자열을 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 인코딩할. |

### 반환 값

필요한 버퍼 크기.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) 메서드


문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 문자 버퍼. |

### 반환 값

필요한 버퍼 크기.

## Encoding::GetByteCount(const char_t *, int) 메서드


문자 버퍼를 인코딩하는 데 필요한 문자 수를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 문자 버퍼. |
| count | int | [Buffer](../../../system/buffer/) 크기. |

### 반환 값

필요한 버퍼 크기.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)