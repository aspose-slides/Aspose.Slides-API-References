---
title: GetChars()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 바이트 버퍼를 디코딩한 결과 얻어지는 문자를 반환합니다.
type: docs
weight: 92
url: /ko/system.text/utf7encoding/getchars/
---
## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |
| byte_index | int | 입력 버퍼 오프셋. |
| byte_count | int | 입력 버퍼 크기. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| char_index | int | 출력 버퍼 오프셋. |

### 반환 값

작성된 문자 수.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |
| byte_count | int | 입력 버퍼 크기. |
| chars | char_t * | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| char_count | int | 출력 버퍼 크기. |

### 반환 값

작성된 문자 수.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |
| byte_index | int | 입력 버퍼 오프셋. |
| byte_count | int | 입력 버퍼 크기. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| char_index | int | 출력 버퍼 오프셋. |

### 반환 값

작성된 문자 수.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |
| index | int | 입력 버퍼 오프셋. |
| count | int | 입력 버퍼 크기. |

### 반환 값

[Buffer](../../../system/buffer/) 디코딩된 문자 수.

## UTF7Encoding::GetChars(ArrayPtr\<uint8_t\>) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |

### 반환 값

[Buffer](../../../system/buffer/) 디코딩된 문자 수.

## UTF7Encoding::GetChars(const uint8_t *, int, char_t *, int) 메서드

디코딩된 바이트 버퍼에서 얻은 문자를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/)에서 바이트를 읽기 위해. |
| byte_count | int | 입력 버퍼 크기. |
| chars | char_t * | [Buffer](../../../system/buffer/)에 문자를 넣기 위해. |
| char_count | int | 출력 버퍼 크기. |

### 반환 값

작성된 문자 수.

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [UTF7Encoding](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)