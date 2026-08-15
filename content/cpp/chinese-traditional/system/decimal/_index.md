---
title: Decimal
second_title: Aspose.Slides for C++ API 參考
description: "表示十進制數字。此類型應分配於堆疊上，並以值或引用方式傳遞給函式。切勿使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 261
url: /zh-hant/system/decimal/
---
## Decimal 類別

Represents a decimal number. This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Decimal
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | 將兩個指定的 [Decimal](./) 值相加。 |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | 傳回大於或等於指定值的最小整數值。 |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | 判斷由第一個 [Decimal](./) 物件表示的值是否小於、等於或大於由第二個 [Decimal](./) 物件表示的值。 |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | 判斷由目前物件表示的值是否小於、等於或大於由指定物件表示的值。 |
| [Decimal](./decimal/)() | 建立表示 0 的實例。 |
| [Decimal](./decimal/)(std::int8_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::int16_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::int32_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::int64_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::uint8_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::uint16_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::uint32_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(std::uint64_t) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(**float**) | 建立表示指定值的實例。 |
| [Decimal](./decimal/)(**double**) | 建立表示指定值的實例。 |
| explicit  [Decimal](./decimal/)(const std::string\&) | 建立一個實例，其值的字串表示是以 std::string 類別的實例指定的。 |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | 從指定的組件建構一個 [Decimal](./) 物件。 |
| [Decimal](./decimal/)(const [Decimal](./)\&) | 建立一個 [Decimal](./) 類別的實例，表示與指定 [Decimal](./) 物件相同的數字。 |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | 從包含二進位表示的整數陣列建構 [Decimal](./) 類別的實例。 |
| [Decimal](./decimal/)(std::nullptr_t) | 總是拋出 ArgumentNullException。 |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | 建構一個表示指定值的 [Decimal](./) 類別實例。 |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | 將兩個指定的 [Decimal](./) 值相除。 |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | 判斷目前物件與指定物件所表示的值是否相等。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 判斷目前物件與指定物件所表示的值是否相等。 |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | 判斷指定的兩個物件所表示的值是否相等。 |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | 傳回小於或等於指定值的最大整數值。 |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) 指定的 OLE 貨幣值為相等的 [Decimal](./) 值。未實作。 |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | 將指定的 [Decimal](./) 物件轉換為其所表示之值的二進位表示。 |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) 指定的 [Decimal](./) 值為位元組陣列。 |
| int [GetHashCode](./gethashcode/)() const | 傳回目前物件的雜湊碼。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | 取得物件類型代碼。 |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | 將兩個指定的 [Decimal](./) 值相乘。 |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | 傳回一個新的 [Decimal](./) 類別實例，表示對指定物件所表示的值取負後的結果。 |
| explicit  [operator bool](./operator_bool/)() const | 將目前物件所表示的值轉換為布林值。 |
| explicit  [operator double](./operator_double/)() const | 將目前物件所表示的值轉換為雙精度浮點數。 |
| explicit  [operator float](./operator_float/)() const | 將目前物件所表示的值轉換為單精度浮點數。 |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | 判斷目前物件與指定物件所表示的值是否不相等。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 判斷目前物件所表示的值是否不同於 0。 |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | 傳回一個新的 [Decimal](./) 類別實例，表示以目前物件與指定物件所表示的值進行取模運算的結果。 |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | 將目前物件指派為以目前與指定物件所表示的值進行取模運算的結果的新值。 |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | 傳回一個新的 [Decimal](./) 類別實例，表示目前與指定物件所表示的值相乘的結果。 |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | 將目前物件指派為目前與指定物件所表示的值相乘的結果的新值。 |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | 傳回一個新的 [Decimal](./) 類別實例，表示目前與指定物件所表示的值之和。 |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | 將目前物件所表示的值遞增。 |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | 將目前物件指派為目前與指定物件所表示的值之和的新值。 |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | 傳回一個新的 [Decimal](./) 類別實例，表示從目前物件所表示的值減去指定物件所表示的值的結果。 |
| [Decimal](./) [operator-](./operator_minus/)() const | 傳回一個新的 [Decimal](./) 類別實例，表示對目前物件所表示的值取負的結果。 |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | 將目前物件所表示的值遞減。 |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | 將目前物件指派為從目前物件所表示的值減去指定物件所表示的值的結果的新值。 |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | 傳回一個新的 [Decimal](./) 類別實例，表示將目前物件所表示的值除以指定物件所表示的值的結果。 |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | 將目前物件指派為將目前物件所表示的值除以指定物件所表示的值的結果的新值。 |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | 判斷目前物件所表示的值是否小於指定物件所表示的值。 |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | 判斷目前物件所表示的值是否小於或等於指定物件所表示的值。 |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | 將指定物件所表示的值指派給目前物件。 |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | 判斷目前物件與指定物件所表示的值是否相等。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 判斷目前物件所表示的值是否為 0。 |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | 判斷目前物件所表示的值是否大於指定物件所表示的值。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | 判斷目前物件所表示的值是否大於或等於指定物件所表示的值。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | 將十進位數字的字串表示轉換為等效的 [Decimal](./) 類別實例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | 將十進位數字的字串表示使用指定的樣式轉換為等效的 [Decimal](./) 類別實例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將十進位數字的字串表示使用指定的格式提供者轉換為等效的 [Decimal](./) 類別實例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將十進位數字的字串表示使用指定的樣式與格式提供者轉換為等效的 [Decimal](./) 類別實例。 |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | 計算兩個 [Decimal](./) 值相除後的餘數。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | 將指定的值四捨五入至最接近的整數。參數指定當指定值等距於兩個最接近的數字時函式的行為。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | 將指定的值四捨五入至具有指定小數位數的最接近值。參數指定當指定值等距於兩個最接近的數字時函式的行為。 |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | 從指定的 [Decimal](./) 值中減去另一個指定的值。 |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | 將 [Decimal](./) 值轉換為無號 8 位元整數值。 |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | 將 [Decimal](./) 值轉換為雙精度浮點數。 |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | 將 [Decimal](./) 值轉換為有號 16 位元整數值。 |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | 將 [Decimal](./) 值轉換為有號 32 位元整數值。 |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | 將 [Decimal](./) 值轉換為有號 64 位元整數值。 |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) 指定的 [Decimal](./) 值為相等的 OLE 貨幣值。未實作。 |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | 將 [Decimal](./) 值轉換為有號 8 位元整數值。 |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | 將 [Decimal](./) 值轉換為單精度浮點數。 |
| std::string [ToStdString](./tostdstring/)() const | 傳回一個 std::string 實例，包含物件所表示的值的字串表示。 |
| [String](../string/) [ToString](./tostring/)() const | 傳回物件所表示的值的字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用特定文化的格式資訊將目前物件轉換為字串。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的字串格式以及指定 [IFormatProvider](../iformatprovider/) 物件提供的特定文化格式資訊，將目前物件轉換為其字串表示。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | 傳回物件所表示的值的字串表示。供內部使用。 |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | 將 [Decimal](./) 值轉換為無號 16 位元整數值。 |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | 將 [Decimal](./) 值轉換為無號 32 位元整數值。 |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | 將 [Decimal](./) 值轉換為無號 64 位元整數值。 |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | 傳回 [Decimal](./) 物件，該物件表示指定 [Decimal](./) 物件所表示的值，捨棄所有小數位後的整數部分相等的值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | 將包含數字字串表示的指定字串轉換為等效的 [Decimal](./) 值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | 使用提供的格式資訊與數字樣式，將包含數字字串表示的指定字串轉換為等效的 [Decimal](./) 值。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 傳回一個參考，指向表示 [Decimal](./) 類別型別資訊的 [TypeInfo](../typeinfo/) 物件。 |
| [~Decimal](./~decimal/)() | 解構子。 |

## 欄位

| 欄位 | 描述 |
| --- | --- |
| static [MaxValue](./maxvalue/) | 代表 [Decimal](./) 類別可以表示的最大數字。 |
| static [MinusOne](./minusone/) | 代表數字 -1。 |
| static [MinValue](./minvalue/) | 代表 [Decimal](./) 類別可以表示的最小數字。 |
| static [One](./one/) | 代表數字 1。 |
| static [Zero](./zero/) | 代表數字 0。 |

## 型別別名

| 型別別名 | 描述 |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type 的別名。 |

## 備註



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
此程式碼範例會產生以下輸出:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)