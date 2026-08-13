---
title: GetBytes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.
type: docs
weight: 66
url: /ko/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자들. |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자들. |
| char_count | int | 변환할 문자 수. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_count | int | 출력 버퍼 크기. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 인코딩할 [String](../../../system/string/). |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자들. |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | 인코딩할 문자들. |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | 인코딩할 문자들. |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 인코딩할 [String](../../../system/string/). |
| char_index | int | 문자 슬라이스 시작 위치. |
| char_count | int | 변환할 문자 수. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_index | int | 출력 버퍼 오프셋. |

### Return Value

작성된 바이트 수.

## UTF7Encoding::GetBytes(const String\&) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | 인코딩할 [String](../../../system/string/). |

### Return Value

[Buffer](../../../system/buffer/) 인코딩되는 문자들의 표현을 보유하는.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자들. |
| index | int | 문자 슬라이스 시작 위치. |
| count | int | 변환할 문자 수. |

### Return Value

[Buffer](../../../system/buffer/) 인코딩되는 문자들의 표현을 보유하는.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | 인코딩할 문자들. |
| index | int | 문자 슬라이스 시작 위치. |
| count | int | 변환할 문자 수. |

### Return Value

[Buffer](../../../system/buffer/) 인코딩되는 문자들의 표현을 보유하는.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | 인코딩할 문자들. |
| index | int | 문자 슬라이스 시작 위치. |
| count | int | 변환할 문자 수. |

### Return Value

[Buffer](../../../system/buffer/) 인코딩되는 문자들의 표현을 보유하는.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | 인코딩할 문자들. |

### Return Value

[Buffer](../../../system/buffer/) 인코딩되는 문자들의 표현을 보유하는.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) method


문자 버퍼를 인코딩하여 생성된 바이트를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | 인코딩할 문자들. |
| char_count | int | 변환할 문자 수. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| byte_count | int | 출력 버퍼 크기. |

### Return Value

작성된 바이트 수.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)