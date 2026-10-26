---
title: Buffer
second_title: Aspose.Slides for C++ API 레퍼런스
description: 원시 바이트 배열을 조작하는 메서드를 포함합니다. 이 타입은 정적이며 인스턴스 서비스를 제공하지 않습니다. 어떤 방법으로도 인스턴스를 생성해서는 안 됩니다.
type: docs
weight: 144
url: /ko/system/buffer/
---
## Buffer 클래스

Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Buffer
```

## 메서드

| 메서드 | 설명 |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | 지정된 바이트 수를 소스 버퍼에서 대상 버퍼로 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | 두 개의 지정된 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 두 개의 지정된 타입 배열을 원시 바이트 배열로 해석하고, 하나에서 다른 하나로 데이터를 복사합니다. |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | 지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다. |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | 지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다. |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | 지정된 배열의 모든 요소가 차지하는 바이트 수를 결정합니다. |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에서 바이트 값을 검색합니다. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에서 바이트 값을 검색합니다. |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에서 바이트 값을 검색합니다. |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다. |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다. |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | 지정된 타입 배열을 원시 바이트 배열로 해석하고, 지정된 바이트 오프셋에 지정된 바이트 값을 설정합니다. |

## 비고



```cpp
#include <system/buffer.h>

using namespace System;

void Print(const SmartPtr<Array<uint8_t>> &source, int size)
{
  for (auto i = 0; i < size; i++)
  {
    std::cout << static_cast<int>(source[i]) << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // 배열을 생성하고 채웁니다.
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // 배열 항목을 출력합니다.
  Print(first, SIZE);

  // 첫 번째 배열의 일부를 포함하는 배열을 생성합니다.
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // 두 번째 배열의 항목을 출력합니다.
  Print(second, SIZE / 2);

  // 인덱스 0의 항목 값을 설정하고 배열 항목을 출력합니다.
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
이 코드 예제는 다음 출력 결과를 생성합니다:
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## 참조

* 네임스페이스 [System](../)
* 라이브러리 [Aspose.Slides](../../)