---
title: GetCharCount()
second_title: Aspose.Slides for C++ API 참조
description: 바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.
type: docs
weight: 79
url: /ko/system.text/utf7encoding/getcharcount/
---
## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트입니다. |
| index | int | 슬라이스 시작 위치입니다. |
| count | int | 슬라이스 크기입니다. |

### 반환값

문자 수.

## UTF7Encoding::GetCharCount(const uint8_t *, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.

```cpp
int System::Text::UTF7Encoding::GetCharCount(const uint8_t *bytes, int count) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코딩할 바이트입니다. |
| count | int | 바이트 수입니다. |

### 반환값

문자 수.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>, int, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트입니다. |
| index | int | 슬라이스 시작 위치입니다. |
| count | int | 슬라이스 크기입니다. |

### 반환값

문자 수.

## UTF7Encoding::GetCharCount(ArrayPtr\<uint8_t\>) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(ArrayPtr<uint8_t> bytes)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 디코딩할 바이트입니다. |

### 반환값

문자 수.

## UTF7Encoding::GetCharCount(const uint8_t *, int) 메서드

바이트 버퍼를 디코딩하는 데 필요한 문자 수를 반환합니다.

```cpp
virtual int System::Text::Encoding::GetCharCount(const uint8_t *bytes, int count)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| bytes | const **uint8_t** * | 디코딩할 바이트입니다. |
| count | int | 바이트 수입니다. |

### 반환값

문자 수.

## 참고

* 타입 정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [UTF7Encoding](../)
* 네임스페이스 [System::Text](../../)
* 라이브러리 [Aspose.Slides](../../../)