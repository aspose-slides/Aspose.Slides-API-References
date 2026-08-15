---
title: Buffer
second_title: Aspose.Slides for C++ API 參考
description: 包含操作原始位元組陣列的方法。這是一個沒有實例服務的靜態型別。無論如何都不應該建立其實例。
type: docs
weight: 144
url: /zh-hant/system/buffer/
---
## Buffer 類別

Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Buffer
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | 將指定數量的位元組從來源緩衝區複製到目標緩衝區。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 將兩個指定的具類型陣列視為原始位元組陣列，並將資料從其中一個複製到另一個。 |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | 確定指定陣列中所有元素佔用的位元組數。 |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | 確定指定陣列中所有元素佔用的位元組數。 |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | 確定指定陣列中所有元素佔用的位元組數。 |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處取得位元組值。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處取得位元組值。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處取得位元組值。 |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。 |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。 |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | 將指定的具類型陣列視為原始位元組陣列，並在指定的位元組偏移處設定指定的位元組值。 |

## 備註

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
  // 創建並填充陣列。
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // 列印陣列項目。
  Print(first, SIZE);

  // 建立包含第一個陣列部分的陣列。
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // 列印第二個陣列的項目。
  Print(second, SIZE / 2);

  // 設定索引 0 處的項目值，並列印陣列項目。
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
此程式碼範例產生以下輸出：
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```


## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)