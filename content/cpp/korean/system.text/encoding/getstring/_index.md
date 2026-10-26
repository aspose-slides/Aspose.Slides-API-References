---
title: GetString()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 버퍼의 바이트를 문자열로 디코딩합니다.
type: docs
weight: 313
url: /ko/system.text/encoding/getstring/
---
## Encoding::GetString(uint8_t *, int) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
virtual String System::Text::Encoding::GetString(uint8_t *bytes, int byte_count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |
| byte_count | int | 입력 버퍼 크기. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(const ReadOnlySpan\<uint8_t\>\&) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
String System::Text::Encoding::GetString(const ReadOnlySpan<uint8_t> &bytes)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const [ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(ArrayPtr\<uint8_t\>) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>\&) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> &bytes)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\>\& | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(ArrayPtr\<uint8_t\>, int, int) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
virtual String System::Text::Encoding::GetString(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |
| index | int | 입력 버퍼 오프셋. |
| count | int | 입력 버퍼 크기. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(const System::Details::ArrayView\<uint8_t\>\&, int, int) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
virtual String System::Text::Encoding::GetString(const System::Details::ArrayView<uint8_t> &bytes, int index, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | const System::Details::ArrayView\<**uint8_t**\>\& | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |
| index | int | 입력 버퍼 오프셋. |
| count | int | 입력 버퍼 크기. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## Encoding::GetString(System::Details::StackArray\<uint8_t, N\>, int, int) 메서드

버퍼의 바이트를 문자열로 디코딩합니다.

```cpp
template<std::size_t> String System::Text::Encoding::GetString(System::Details::StackArray<uint8_t, N> bytes, int index, int count)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| bytes | System::Details::StackArray\<**uint8_t**, N\> | [Buffer](../../../system/buffer/) 에서 바이트를 읽기 위해. |
| index | int | 입력 버퍼 오프셋. |
| count | int | 입력 버퍼 크기. |

### 반환값

[String](../../../system/string/) 디코딩된 문자.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [Encoding](../)
* 클래스 [ReadOnlySpan](../../../system/readonlyspan/)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)