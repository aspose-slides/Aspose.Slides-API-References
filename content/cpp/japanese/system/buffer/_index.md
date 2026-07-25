---
title: Buffer
second_title: Aspose.Slides for C++ APIリファレンス
description: 生バイト配列を操作するメソッドを含みます。これはインスタンスサービスを持たない静的型です。いかなる方法でもインスタンスを作成してはなりません。
type: docs
weight: 144
url: /ja/system/buffer/
---
## Buffer クラス


Contains methods that manipulate raw byte arrays. This is a static type with no instance services. You should never create instances of it by any means.

```cpp
class Buffer
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | 指定されたバイト数をソースバッファからデスティネーションバッファへコピーします。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 指定された 2 つの型付き配列を生バイト配列として解釈し、一方からもう一方へデータをコピーします。 |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | 指定された配列のすべての要素が占めるバイト数を決定します。 |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | 指定された配列のすべての要素が占めるバイト数を決定します。 |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | 指定された配列のすべての要素が占めるバイト数を決定します。 |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置のバイト値を取得します。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置のバイト値を取得します。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置のバイト値を取得します。 |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置に指定されたバイト値を設定します。 |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置に指定されたバイト値を設定します。 |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | 指定された型付き配列を生バイト配列として解釈し、指定されたバイトオフセット位置に指定されたバイト値を設定します。 |
## 備考



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
  // 配列を作成して埋めます。
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // 配列の要素を出力します。
  Print(first, SIZE);

  // 最初の配列の一部を含む配列を作成します。
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // 二番目の配列の要素を出力します。
  Print(second, SIZE / 2);

  // インデックス0の要素の値を設定し、配列の要素を出力します。
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
このコード例は以下の出力を生成します。
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)