---
title: ToInt32()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 32비트 정수 값으로 변환합니다.
type: docs
weight: 66
url: /ko/system/bitconverter/toint32/
---
## BitConverter::ToInt32(const System::ArrayPtr\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 32비트 정수 값으로 변환합니다.

```cpp
static int System::BitConverter::ToInt32(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/)에 포함된 바이트를 변환합니다 |
| startIndex | int | [Index](../../index/) 배열에서 바이트 변환을 시작할 인덱스 |

### 반환 값

변환 결과인 32비트 정수 값

## BitConverter::ToInt32(const System::Details::ArrayView\<uint8_t\>\&, int) 메서드


지정된 인덱스에서 시작하는 지정된 배열의 네 바이트를 32비트 정수 값으로 변환합니다.

```cpp
static int System::BitConverter::ToInt32(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | 바이트를 변환하는 ArrayView |
| startIndex | int | [Index](../../index/) 배열에서 바이트 변환을 시작할 인덱스 |

### 반환 값

변환 결과인 32비트 정수 값

## 참고

* 타입정의 [ArrayPtr](../../arrayptr/)
* 클래스 [BitConverter](../)
* 네임스페이스 [System](../../)
* 라이브러리 [Aspose.Slides](../../../)