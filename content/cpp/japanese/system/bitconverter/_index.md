---
title: BitConverter
second_title: Aspose.Slides for C++ API リファレンス
description: シーケンスのバイトを値型に変換したりその逆を行うメソッドを含みます。これはインスタンスサービスのない静的型です。いかなる方法でもインスタンスを作成すべきではありません。
type: docs
weight: 66
url: /ja/system/bitconverter/
---
## BitConverter クラス

シーケンスのバイトを値型に変換したりその逆を行うメソッドを含みます。これはインスタンスサービスのない静的型です。いかなる方法でもインスタンスを作成すべきではありません。

```cpp
class BitConverter
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| static **bool** [_IsLittleEndian](./_islittleendian/)() | 現在のアーキテクチャのエンディアンを示します。 |
| static **int64_t** [DoubleToInt64Bits](./doubletoint64bits/)(**double**) | 指定された倍精度浮動小数点値のバイナリ表現と等しいバイナリ表現を持つ 64 ビット整数値を返します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**bool**) | 指定されたブール値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(char_t) | 指定された char_t 値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int16_t**) | 指定された 16 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(int) | 指定された 32 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**int64_t**) | 指定された 64 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint16_t**) | 指定された符号なし 16 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint32_t**) | 指定された符号なし 32 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**uint64_t**) | 指定された符号なし 64 ビット整数値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**float**) | 指定された単精度浮動小数点値をバイト配列に変換します。 |
| static [System::ArrayPtr](../arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(**double**) | 指定された倍精度浮動小数点値をバイト配列に変換します。 |
| static **double** [Int64BitsToDouble](./int64bitstodouble/)(**int64_t**) | 指定された値に等価な倍精度浮動小数点値を返します。 |
| static **bool** [ToBoolean](./toboolean/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 1 バイトをブール値に変換します。 |
| static **bool** [ToBoolean](./toboolean/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 1 バイトをブール値に変換します。 |
| static char_t [ToChar](./tochar/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを char_t 値に変換します。 |
| static char_t [ToChar](./tochar/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを char_t 値に変換します。 |
| static **double** [ToDouble](./todouble/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを倍精度浮動小数点値に変換します。 |
| static **double** [ToDouble](./todouble/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを倍精度浮動小数点値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを 16 ビット整数値に変換します。 |
| static **int16_t** [ToInt16](./toint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを 16 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを 32 ビット整数値に変換します。 |
| static int [ToInt32](./toint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを 32 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを 64 ビット整数値に変換します。 |
| static **int64_t** [ToInt64](./toint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを 64 ビット整数値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを単精度浮動小数点値に変換します。 |
| static **float** [ToSingle](./tosingle/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを単精度浮動小数点値に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, **bool**, const [String](../string/)\&) | 指定されたバイト配列のすべての値を 16 進数文字列に変換します。使用する文字の大文字小文字と各バイトペア間に挿入する区切り文字は対応する引数で指定します。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始してバイト配列の値を 16 進数文字列に変換します。 |
| static [String](../string/) [ToString](./tostring/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int, int) | 指定されたバイト配列の範囲の値を 16 進数文字列に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを符号なし 16 ビット整数値に変換します。 |
| static **uint16_t** [ToUInt16](./touint16/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 2 バイトを符号なし 16 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを符号なし 32 ビット整数値に変換します。 |
| static **uint32_t** [ToUInt32](./touint32/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 4 バイトを符号なし 32 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを符号なし 64 ビット整数値に変換します。 |
| static **uint64_t** [ToUInt64](./touint64/)(const System::Details::ArrayView\<**uint8_t**\>\&, int) | 指定されたインデックスから開始する配列の 8 バイトを符号なし 64 ビット整数値に変換します。 |

## フィールド

| フィールド | 説明 |
| --- | --- |
| static [IsLittleEndian](./islittleendian/) | 現在のアーキテクチャのエンディアンを示します。アーキテクチャがリトルエンディアンの場合は true、そうでない場合は false です。 |

## 備考



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
  // 値を作成して出力します。
  int anInt = 1234567890;
  double aDouble = 0.123456789;

  // 値とそのバイト列を出力します。
  Print(anInt);
  Print(aDouble);

  return 0;
}
/*
このコード例は次の出力を生成します:
1234567890 d229649
0.123457 5f633937dd9abf3f
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)