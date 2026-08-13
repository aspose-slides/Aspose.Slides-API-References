---
title: GetBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.
type: docs
weight: 248
url: /ko/system.text/encoding/getbytes/
---
## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 에 문자를 넣습니다. |
| byte_index | int | Output buffer offset. |

### 반환값

작성된 바이트 수.

## Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) 에 문자를 넣습니다. |
| byte_index | int | Output buffer offset. |

### 반환값

작성된 바이트 수.

## Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Characters to encode. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) 에 문자를 넣습니다. |
| byte_index | int | Output buffer offset. |

### 반환값

작성된 바이트 수.

## Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 을 인코딩합니다. |
| char_index | int | Character slice beginning. |
| char_count | int | Number of characters to convert. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 에 문자를 넣습니다. |
| byte_index | int | Output buffer offset. |

### 반환값

작성된 바이트 수.

## Encoding::GetBytes(const String\&) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) 을 인코딩합니다. |

### 반환값

[Buffer](../../../system/buffer/) 은 인코딩된 문자의 표현을 보유합니다.

## Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### 반환값

[Buffer](../../../system/buffer/) 은 인코딩된 문자의 표현을 보유합니다.

## Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### 반환값

[Buffer](../../../system/buffer/) 은 인코딩된 문자의 표현을 보유합니다.

## Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Characters to encode. |
| index | int | Character slice beginning. |
| count | int | Number of characters to convert. |

### 반환값

[Buffer](../../../system/buffer/) 은 인코딩된 문자의 표현을 보유합니다.

## Encoding::GetBytes(ArrayPtr\<char_t\>) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Characters to encode. |

### 반환값

[Buffer](../../../system/buffer/) 은 인코딩된 문자의 표현을 보유합니다.

## Encoding::GetBytes(const char_t *, int, uint8_t *, int) 메서드

문자 버퍼를 인코딩한 결과 바이트를 가져옵니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Characters to encode. |
| char_count | int | Number of characters to convert. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 에 문자를 넣습니다. |
| byte_count | int | Output buffer size. |

### 반환값

작성된 바이트 수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Encoding](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)