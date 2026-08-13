---
title: ToDouble()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 배열에서 지정된 인덱스부터 시작하여 8바이트를 변환하여 배정밀도 부동 소수점 값으로 변환합니다.
type: docs
weight: 144
url: /ko/system/bitconverter/todouble/
---
## BitConverter::ToDouble(const System::ArrayPtr\<uint8_t\>\&, int) method

지정된 배열에서 지정된 인덱스부터 시작하여 8바이트를 변환하여 배정밀도 부동 소수점 값으로 변환합니다.

```cpp
static double System::BitConverter::ToDouble(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작할 배열 인덱스 |

### 반환 값

배정밀도 부동 소수점 값 변환 결과

## BitConverter::ToDouble(const System::Details::ArrayView\<uint8_t\>\&, int) method

지정된 배열에서 지정된 인덱스부터 시작하여 8바이트를 변환하여 배정밀도 부동 소수점 값으로 변환합니다.

```cpp
static double System::BitConverter::ToDouble(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작할 배열 인덱스 |

### 반환 값

배정밀도 부동 소수점 값 변환 결과

## 참조

* Typedef [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)