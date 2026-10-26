---
title: ToChar()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 시작하여 지정된 배열의 두 바이트를 char_t 값으로 변환합니다.
type: docs
weight: 40
url: /ko/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 두 바이트를 char_t 값으로 변환합니다.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스 |

### 반환 값

char_t value resulting from conversion

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 두 바이트를 char_t 값으로 변환합니다.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스 |

### 반환 값

char_t value resulting from conversion

## 또보기

* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)