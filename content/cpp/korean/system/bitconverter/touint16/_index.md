---
title: ToUInt16()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에서 시작하는 지정된 배열의 두 바이트를 변환하여 부호 없는 16비트 정수 값을 반환합니다.
type: docs
weight: 92
url: /ko/system/bitconverter/touint16/
---
## BitConverter::ToUInt16(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 인덱스부터 시작하는 지정된 배열에서 두 바이트를 변환하여 부호 없는 16비트 정수 값을 반환합니다.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 배열에서 바이트를 변환하기 시작하는 인덱스 |

### 반환값

변환 결과로 얻어지는 부호 없는 16비트 정수 값

## BitConverter::ToUInt16(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 인덱스부터 시작하는 지정된 배열에서 두 바이트를 변환하여 부호 없는 16비트 정수 값을 반환합니다.

```cpp
static uint16_t System::BitConverter::ToUInt16(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 변환할 바이트를 포함하는 ArrayView |
| startIndex | int | [Index](../../index/) 배열에서 바이트를 변환하기 시작하는 인덱스 |

### 반환값

변환 결과로 얻어지는 부호 없는 16비트 정수 값

## 참고

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)