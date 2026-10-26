---
title: Buffer
second_title: Aspose.Slides for C++ API 参考
description: 包含操作原始字节数组的方法。此为静态类型，没有实例服务。绝不应以任何方式创建其实例。
type: docs
weight: 144
url: /zh/system/buffer/
---
## Buffer 类

包含操作原始字节数组的方法。此为静态类型，没有实例服务。绝不应以任何方式创建其实例。

```cpp
class Buffer
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static void [BlockCopy](./blockcopy/)(const **uint8_t** *, int, **uint8_t** *, int, int) | 将指定数量的字节从源缓冲区复制到目标缓冲区。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, const [SharedPtr](../sharedptr/)\<[ArrayBase](../arraybase/)\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::ArrayView\<TDst\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::ArrayView\<TSrc\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TSrc\>\>\&, int, const System::Details::StackArray\<TDst, ND\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static void [BlockCopy](./blockcopy/)(const System::Details::StackArray\<TSrc, NS\>\&, int, const [SharedPtr](../sharedptr/)\<[Array](../array/)\<TDst\>\>\&, int, int) | 将两个指定的类型化数组解释为原始字节数组，并将数据从其中一个复制到另一个。 |
| static int [ByteLength](./bytelength/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&) | 确定指定数组的所有元素所占用的字节数。 |
| static int [ByteLength](./bytelength/)(const System::Details::ArrayView\<T\>\&) | 确定指定数组的所有元素所占用的字节数。 |
| static int [ByteLength](./bytelength/)(const System::Details::StackArray\<T, N\>\&) | 确定指定数组的所有元素所占用的字节数。 |
| static **uint8_t** [GetByte](./getbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处检索字节值。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::ArrayView\<T\>\&, int) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处检索字节值。 |
| static **uint8_t** [GetByte](./getbyte/)(const System::Details::StackArray\<T, N\>\&, int) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处检索字节值。 |
| static void [SetByte](./setbyte/)(const [SharedPtr](../sharedptr/)\<[Array](../array/)\<T\>\>\&, int, **uint8_t**) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。 |
| static void [SetByte](./setbyte/)(const System::Details::ArrayView\<T\>\&, int, **uint8_t**) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。 |
| static void [SetByte](./setbyte/)(const System::Details::StackArray\<T, N\>\&, int, **uint8_t**) | 将指定的类型化数组解释为原始字节数组，并在指定的字节偏移处设置指定的字节值。 |

## 备注

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
  // 创建并填充数组。
  const int SIZE = 16;
  auto first = MakeObject<Array<uint8_t>>(SIZE);
  for (auto i = 0; i < SIZE; ++i)
  {
    first[i] = static_cast<uint8_t>(i * 2);
  }

  // 打印数组项。
  Print(first, SIZE);

  // 创建一个包含前一个数组一部分的数组。
  auto second = MakeObject<Array<uint8_t>>(SIZE / 2);
  Buffer::BlockCopy(first, SIZE / 2, second, 0, SIZE / 2);

  // 打印第二个数组的项。
  Print(second, SIZE / 2);

  // 设置索引 0 处项的值并打印数组项。
  Buffer::SetByte(second, 0, 128);
  Print(second, SIZE / 2);

  return 0;
}
/*
此代码示例产生以下输出：
0 2 4 6 8 10 12 14 16 18 20 22 24 26 28 30
16 18 20 22 24 26 28 30
128 18 20 22 24 26 28 30
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)