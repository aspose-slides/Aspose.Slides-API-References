---
title: ToBoolean()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 인덱스에서 시작하는 지정된 배열의 한 바이트를 부울 값으로 변환합니다.
type: docs
weight: 27
url: /ko/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 한 바이트를 부울 값으로 변환합니다.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) 변환할 바이트를 포함하는 |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스 |

### 반환 값

[Boolean](../../boolean/) 변환 결과값

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드

지정된 인덱스에서 시작하는 지정된 배열의 한 바이트를 부울 값으로 변환합니다.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 변환할 바이트를 포함하는 ArrayView |
| startIndex | int | [Index](../../index/) 변환을 위해 바이트를 가져오기 시작하는 배열 내 인덱스 |

### 반환 값

[Boolean](../../boolean/) 변환 결과값

## 참고

* 타입 정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)