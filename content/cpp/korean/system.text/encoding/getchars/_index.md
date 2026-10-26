---
title: GetChars()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바이트 버퍼를 디코딩하여 얻은 문자를 반환합니다.
type: docs
weight: 274
url: /ko/system.text/encoding/getchars/
---
## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) 메서드

바이트 버퍼를 디코딩하여 얻은 문자들을 반환합니다.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 읽을 바이트 |
| byte_index | int | 입력 버퍼 오프셋 |
| byte_count | int | 입력 버퍼 크기 |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) 문자를 넣을 대상 |
| char_index | int | 출력 버퍼 오프셋 |

### 반환 값

작성된 문자의 개수.

## Encoding::GetChars(ArrayPtr\<uint8_t\>, int, int) 메서드

바이트 버퍼를 디코딩하여 얻은 문자들을 반환합니다.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 읽을 바이트 |
| index | int | 입력 버퍼 오프셋 |
| count | int | 입력 버퍼 크기 |

### 반환 값

[Buffer](../../../system/buffer/) 디코딩된 문자

## Encoding::GetChars(ArrayPtr\<uint8_t\>) 메서드

바이트 버퍼를 디코딩하여 얻은 문자들을 반환합니다.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) 읽을 바이트 |

### 반환 값

[Buffer](../../../system/buffer/) 디코딩된 문자

## Encoding::GetChars(const uint8_t *, int, char_t *, int) 메서드

바이트 버퍼를 디코딩하여 얻은 문자들을 반환합니다.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) 읽을 바이트 |
| byte_count | int | 입력 버퍼 크기 |
| chars | char_t * | [Buffer](../../../system/buffer/) 문자를 넣을 대상 |
| char_count | int | 출력 버퍼 크기 |

### 반환 값

작성된 문자의 개수.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Encoding](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)