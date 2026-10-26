---
title: BitConverter
second_title: Aspose.Slides for C++ API 参考
description: 包含执行字节序列与值类型相互转换的方法。这是一个静态类型，没有实例服务。绝不应以任何方式创建其实例。
type: docs
weight: 66
url: /zh/system/bitconverter/
---
## BitConverter 类

包含执行字节序列与值类型相互转换的方法。这是一个静态类型，没有实例服务。绝不能以任何方式创建其实例。

```cpp
class BitConverter
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | 指示当前架构的字节序。 |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | 返回一个 64 位整数值，其二进制表示等于指定双精度浮点值的二进制表示。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | 将指定的布尔值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | 将指定的 char_t 值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | 将指定的 16 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | 将指定的 32 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | 将指定的 64 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | 将指定的无符号 16 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | 将指定的无符号 32 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | 将指定的无符号 64 位整数值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | 将指定的单精度浮点值转换为字节数组。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | 将指定的双精度浮点值转换为字节数组。 |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | 返回一个双精度浮点值，其数值等价于传入的值。 |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的一个字节转换为布尔值。 |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的一个字节转换为布尔值。 |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为 char_t 值。 |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为 char_t 值。 |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为双精度浮点值。 |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为双精度浮点值。 |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为 16 位整数值。 |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为 16 位整数值。 |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为 32 位整数值。 |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为 32 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为 64 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为 64 位整数值。 |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为单精度浮点值。 |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为单精度浮点值。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | 将指定字节数组的所有值转换为其十六进制字符串表示。十六进制表示中使用的字母大小写以及在相邻字节对之间插入的分隔符通过相应的参数指定。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定字节数组的值从指定索引开始转换为其十六进制字符串表示。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | 将指定字节数组的一个范围的值转换为其十六进制字符串表示。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为无符号 16 位整数值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的两个字节转换为无符号 16 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为无符号 32 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的四个字节转换为无符号 32 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为无符号 64 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 将指定数组中从指定索引开始的八个字节转换为无符号 64 位整数值。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | 指示当前架构的字节序。如果架构是小端则为 true，否则为 false。 |

## 备注

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
  // 创建要打印的值。
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // 打印值及其字节。
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
此代码示例产生以下输出:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)