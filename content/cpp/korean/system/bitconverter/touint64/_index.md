---
title: ToUInt64()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 시작하는 지정된 배열의 8바이트를 변환하여 부호 없는 64비트 정수 값을 반환합니다.
type: docs
weight: 118
url: /ko/system/bitconverter/touint64/
---
## BitConverter::ToUInt64(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 8바이트를 변환하여 부호 없는 64비트 정수 값을 반환합니다.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 배열에서 변환용 바이트를 가져오기 시작하는 인덱스 |

### 반환값

변환 결과 얻은 부호 없는 64비트 정수 값

## BitConverter::ToUInt64(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 8바이트를 변환하여 부호 없는 64비트 정수 값을 반환합니다.

```cpp
static uint64_t System::BitConverter::ToUInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 배열에서 변환용 바이트를 가져오기 시작하는 인덱스 |

### 반환값

변환 결과 얻은 부호 없는 64비트 정수 값

## 관련 항목

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)