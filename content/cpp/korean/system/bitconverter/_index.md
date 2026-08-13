---
title: BitConverter
second_title: Aspose.Slides for C++ API 레퍼런스
description: 바이트 시퀀스를 값 타입으로, 그리고 그 반대로 변환하는 메서드를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 66
url: /ko/system/bitconverter/
---
## BitConverter 클래스

바이트 시퀀스를 값 타입으로, 그리고 그 반대로 변환하는 메서드를 포함합니다. 이는 인스턴스 서비스를 제공하지 않는 정적 타입이며, 어떠한 방법으로도 인스턴스를 생성해서는 안 됩니다.

```cpp
class BitConverter
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | 현재 아키텍처의 엔디언 방식을 나타냅니다. |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | 지정된 배정밀도 부동소수점 값의 이진 표현과 동일한 이진 표현을 갖는 64비트 정수 값을 반환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | 지정된 불리언 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | 지정된 char_t 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | 지정된 16비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | 지정된 32비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | 지정된 64비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | 지정된 부호 없는 16비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | 지정된 부호 없는 32비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | 지정된 부호 없는 64비트 정수 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | 지정된 단정밀도 부동소수점 값을 바이트 배열로 변환합니다. |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | 지정된 배정밀도 부동소수점 값을 바이트 배열로 변환합니다. |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | 값과 동등한 배정밀도 부동소수점 값을 반환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 한 바이트를 불리언 값으로 변환합니다. |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 한 바이트를 불리언 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 char_t 값으로 변환합니다. |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 char_t 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 배정밀도 부동소수점 값으로 변환합니다. |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 배정밀도 부동소수점 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 16비트 정수 값으로 변환합니다. |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 16비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 32비트 정수 값으로 변환합니다. |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 32비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 64비트 정수 값으로 변환합니다. |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 64비트 정수 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 단정밀도 부동소수점 값으로 변환합니다. |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 단정밀도 부동소수점 값으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | 지정된 바이트 배열의 모든 값을 16진수 문자열 표현으로 변환합니다. 16진수 표기에 사용할 대소문자와 인접 바이트 쌍 사이에 삽입할 구분자는 해당 인수를 통해 지정됩니다. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하여 지정된 바이트 배열의 값을 16진수 문자열 표현으로 변환합니다. |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | 지정된 바이트 배열의 값 범위를 16진수 문자열 표현으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 두 바이트를 부호 없는 16비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 네 바이트를 부호 없는 32비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 부호 없는 64비트 정수 값으로 변환합니다. |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 지정된 인덱스부터 시작하는 지정된 배열의 여덟 바이트를 부호 없는 64비트 정수 값으로 변환합니다. |

## 필드

| 필드 | 설명 |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | 현재 아키텍처의 엔디언 방식을 나타냅니다. 아키텍처가 little endian이면 true, 그렇지 않으면 false입니다. |

## 참고



```cpp
#include <system/bit_converter.h>
#include <system/smart_ptr.h>

using namespace System;

template <typename T>
void Print(T arg)
{
  std::cout << arg << ' ';

  for (const auto byte: BitConverter::GetBytes(arg))
  {
    std::cout << std::hex << static_cast<int>(byte);
  }

  std::cout << std::endl;
}

int main()
{
  // 출력할 값을 생성합니다.
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // 값과 해당 바이트를 출력합니다.
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
이 코드 예제는 다음과 같은 출력 결과를 생성합니다:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)