---
title: ToInt16()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 시작하여 지정된 배열의 두 바이트를 16비트 정수 값으로 변환합니다.
type: docs
weight: 53
url: /ko/system/bitconverter/toint16/
---
## BitConverter::ToInt16(const System::ArrayPtr\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하여 지정된 배열의 두 바이트를 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::BitConverter::ToInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### 반환 값

16-bit integer value resulting from conversion

## BitConverter::ToInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하여 지정된 배열의 두 바이트를 16비트 정수 값으로 변환합니다.

```cpp
static int16_t System::BitConverter::ToInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView that contains bytes to convert |
| startIndex | int | [Index](../../index/) in the array at which to start taking bytes for conversion |

### 반환 값

16-bit integer value resulting from conversion

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)