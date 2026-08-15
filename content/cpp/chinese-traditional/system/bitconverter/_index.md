---
title: BitConverter
second_title: Aspose.Slides for C++ API 參考
description: 包含執行位元組序列與值類型之間相互轉換的方法。這是一個靜態類型，沒有實例服務。絕不應以任何方式建立其實例。
type: docs
weight: 66
url: /zh-hant/system/bitconverter/
---
## BitConverter 類別


包含將位元組序列轉換為值型別以及反向轉換的方法。這是一個靜態類別，沒有實例服務。絕不應以任何方式建立其實例。

```cpp
class BitConverter
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | 表示目前架構的位元組序 (endianness)。 |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | 返回一個 64 位元整數，其二進位表示等同於指定雙精度浮點數的二進位表示。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | 將指定的布林值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | 將指定的 char_t 值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | 將指定的 16 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | 將指定的 32 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | 將指定的 64 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | 將指定的無號 16 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | 將指定的無號 32 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | 將指定的無號 64 位元整數值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | 將指定的單精度浮點值轉換為位元組陣列。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | 將指定的雙精度浮點值轉換為位元組陣列。 |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | 返回一個雙精度浮點值，其值等同於給定的整數值。 |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將一個位元組轉換為布林值。 |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將一個位元組轉換為布林值。 |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為 char_t 值。 |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為 char_t 值。 |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為雙精度浮點值。 |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為雙精度浮點值。 |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為 16 位元整數值。 |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為 16 位元整數值。 |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為 32 位元整數值。 |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為 32 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為 64 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為 64 位元整數值。 |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為單精度浮點值。 |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為單精度浮點值。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | 將指定位元組陣列的所有值轉換為十六進位字串表示。十六進位表示法中使用的字母大小寫與每對相鄰位元組之間插入的分隔符由相應參數指定。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定索引開始，將指定位元組陣列的值轉換為十六進位字串表示。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | 將指定位元組陣列的一段範圍值轉換為十六進位字串表示。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為無號 16 位元整數值。 |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將兩個位元組轉換為無號 16 位元整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為無號 32 位元整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將四個位元組轉換為無號 32 位元整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為無號 64 位元整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 從指定陣列的指定索引開始，將八個位元組轉換為無號 64 位元整數值。 |
## 欄位

| 欄位 | 說明 |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | 表示目前架構的位元組序。若架構為小端序則為 true，否則為 false。 |
## 附註



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
  // 建立要列印的值。
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // 列印值及其位元組。
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
This code example produces the following output:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## 相關資訊

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)