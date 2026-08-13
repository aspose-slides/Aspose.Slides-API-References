---
title: ToUInt32()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 부호 없는 32비트 정수 값으로 변환합니다.
type: docs
weight: 105
url: /ko/system/bitconverter/touint32/
---
## BitConverter::ToUInt32(const System::ArrayPtr\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 부호 없는 32비트 정수 값으로 변환합니다.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 은(는) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 은(는) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스입니다 |

### 반환 값

변환 결과인 부호 없는 32비트 정수 값

## BitConverter::ToUInt32(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 부호 없는 32비트 정수 값으로 변환합니다.

```cpp
static uint32_t System::BitConverter::ToUInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 은(는) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 은(는) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스입니다 |

### 반환 값

변환 결과인 부호 없는 32비트 정수 값

## 참고

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)