---
title: ToInt64()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 인덱스에서 시작하여 지정된 배열의 8바이트를 64비트 정수 값으로 변환합니다.
type: docs
weight: 79
url: /ko/system/bitconverter/toint64/
---
## BitConverter::ToInt64(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하여 지정된 배열의 8바이트를 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::BitConverter::ToInt64(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 배열에서 바이트 변환을 시작하는 인덱스 |

### Return Value

변환 결과 64비트 정수 값

## BitConverter::ToInt64(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하여 지정된 배열의 8바이트를 64비트 정수 값으로 변환합니다.

```cpp
static int64_t System::BitConverter::ToInt64(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 변환할 바이트를 포함하는 ArrayView |
| startIndex | int | [Index](../../index/) 배열에서 바이트 변환을 시작하는 인덱스 |

### Return Value

변환 결과 64비트 정수 값

## 참고

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)