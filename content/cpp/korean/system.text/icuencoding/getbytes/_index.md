---
title: GetBytes()
second_title: C++용 Aspose.Slides API 참고 문서
description: 문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.
type: docs
weight: 40
url: /ko/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_count | int | 출력 버퍼 크기입니다. |

### 반환값

작성된 바이트 수.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자입니다. |
| char_index | int | 문자 슬라이스 시작 위치입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_index | int | 출력 버퍼 오프셋입니다. |

### 반환값

작성된 바이트 수.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 인코딩할 문자입니다. |
| char_index | int | 문자 슬라이스 시작 위치입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_index | int | 출력 버퍼 오프셋입니다. |

### 반환값

작성된 바이트 수.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | 인코딩할 문자입니다. |
| char_index | int | 문자 슬라이스 시작 위치입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_index | int | 출력 버퍼 오프셋입니다. |

### 반환값

작성된 바이트 수.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/)을(를) 인코딩합니다. |
| char_index | int | 문자 슬라이스 시작 위치입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_index | int | 출력 버퍼 오프셋입니다. |

### 반환값

작성된 바이트 수.

## ICUEncoding::GetBytes(const String\&) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/)을(를) 인코딩합니다. |

### 반환값

[Buffer](../../../system/buffer/)는 인코딩된 문자의 표현을 포함합니다.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자입니다. |
| index | int | 문자 슬라이스 시작 위치입니다. |
| count | int | 변환할 문자 수입니다. |

### 반환값

[Buffer](../../../system/buffer/)는 인코딩된 문자의 표현을 포함합니다.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | 인코딩할 문자입니다. |
| index | int | 문자 슬라이스 시작 위치입니다. |
| count | int | 변환할 문자 수입니다. |

### 반환값

[Buffer](../../../system/buffer/)는 인코딩된 문자의 표현을 포함합니다.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 인코딩할 문자입니다. |
| index | int | 문자 슬라이스 시작 위치입니다. |
| count | int | 변환할 문자 수입니다. |

### 반환값

[Buffer](../../../system/buffer/)는 인코딩된 문자의 표현을 포함합니다.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자입니다. |

### 반환값

[Buffer](../../../system/buffer/)는 인코딩된 문자의 표현을 포함합니다.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) 메서드


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자입니다. |
| char_count | int | 변환할 문자 수입니다. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/)에 문자를 넣습니다. |
| byte_count | int | 출력 버퍼 크기입니다. |

### 반환값

작성된 바이트 수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICUEncoding](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)