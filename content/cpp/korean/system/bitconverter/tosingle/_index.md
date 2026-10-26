---
title: ToSingle()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스부터 시작하여 지정된 배열에서 4바이트를 읽어 단정밀 부동소수점 값으로 변환합니다.
type: docs
weight: 131
url: /ko/system/bitconverter/tosingle/
---
## BitConverter::ToSingle(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 배열에서 지정된 인덱스부터 시작하여 4바이트를 단정밀 부동 소수점 값으로 변환합니다.

```cpp
static float System::BitConverter::ToSingle(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 바이트를 변환하기 위해 포함하는 |
| startIndex | int | [Index](../../index/) 배열에서 변환을 위해 바이트를 가져오기 시작하는 인덱스 |

### 반환값

단정밀 부동 소수점 값 변환 결과

## BitConverter::ToSingle(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 배열에서 지정된 인덱스부터 시작하여 4바이트를 단정밀 부동 소수점 값으로 변환합니다.

```cpp
static float System::BitConverter::ToSingle(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 바이트를 변환하기 위해 포함하는 ArrayView |
| startIndex | int | [Index](../../index/) 배열에서 변환을 위해 바이트를 가져오기 시작하는 인덱스 |

### 반환값

단정밀 부동 소수점 값 변환 결과

## 참조

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)