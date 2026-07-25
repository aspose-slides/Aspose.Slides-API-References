---
title: Byte
second_title: Aspose.Slides の C++ API リファレンス
description: 符号なし 8 ビット整数を操作するためのメソッドを含みます。
type: docs
weight: 157
url: /ja/system/byte/
---
## Byte クラス

符号なし 8 ビット整数を扱うためのメソッドを含みます。

```cpp
class Byte
```

## メソッド

| Method | Description |
| --- | --- |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&) | 指定された文字列（数値の文字列表現を含む）を、対応する 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して、対応する 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して、対応する 8 ビット符号なし整数に変換します。 |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint8_t**\&) | 指定された文字列（数値の文字列表現を含む）を、対応する 8 ビット符号なし整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint8_t**\&) | 指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して、対応する 8 ビット符号なし整数に変換します。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint8_t**\&) |  |

## フィールド

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 可能な最大値。 |
| static constexpr [MinValue](./minvalue/) | 可能な最小値。 |

## 備考



```cpp
#include <system/byte.h>

using namespace System;

int main()
{
  auto b1 = Byte::Parse(u"123");
  std::cout << static_cast<uint32_t>(b1) << std::endl;

  try
  {
    auto b2 = Byte::Parse(u"345");
    std::cout << static_cast<uint32_t>(b2) << std::endl;
  }
  catch (const OverflowException &ex)
  {
    std::cerr << ex.what() << std::endl;
  }

  uint8_t b3 = 0;
  if (Byte::TryParse(u"10", b3))
  {
    std::cout << static_cast<uint32_t>(b3) << std::endl;
  }
  else
  {
    std::cerr << "Something went wrong." << std::endl;
  }

  return 0;
}
/*
このコード例は次の出力を生成します:
123
System::OverflowException: 値が UInt8 の範囲を超えているか、または小さすぎます
10
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)