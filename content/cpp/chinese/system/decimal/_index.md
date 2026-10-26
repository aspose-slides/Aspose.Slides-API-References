---
title: Decimal
second_title: Aspose.Slides for C++ API 参考
description: "表示十进制数。此类型应在栈上分配并通过值或引用传递给函数。永不要使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 261
url: /zh/system/decimal/
---
## Decimal 类

表示十进制数。此类型应在栈上分配并通过值或引用传递给函数。永不要使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class Decimal
```

## 方法

| 方法 | 描述 |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | 将两个指定的 [Decimal](./) 值相加。 |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | 返回大于或等于指定值的最小整数值。 |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | 确定第一个 [Decimal](./) 对象表示的值是小于、等于还是大于第二个 [Decimal](./) 对象表示的值。 |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | 确定当前对象表示的值是小于、等于还是大于指定对象表示的值。 |
| [Decimal](./decimal/)() | 构造一个表示 0 的实例。 |
| [Decimal](./decimal/)(std::int8_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::int16_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::int32_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::int64_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::uint8_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::uint16_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::uint32_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(std::uint64_t) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(**float**) | 构造一个表示指定值的实例。 |
| [Decimal](./decimal/)(**double**) | 构造一个表示指定值的实例。 |
| explicit [Decimal](./decimal/)(const std::string\&) | 构造一个实例，其表示的值的字符串表示形式由 std::string 类的实例指定。 |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | 使用指定的组件构造一个 [Decimal](./) 对象。 |
| [Decimal](./decimal/)(const [Decimal](./)\&) | 构造一个 [Decimal](./) 类的实例，该实例表示与指定 [Decimal](./) 对象相同的数字。 |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | 从包含二进制表示的整数数组构造一个 [Decimal](./) 类的实例。 |
| [Decimal](./decimal/)(std::nullptr_t) | 始终抛出 ArgumentNullException。 |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | 构造一个表示指定值的 [Decimal](./) 类的实例。 |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | 对两个指定的 [Decimal](./) 值进行除法。 |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | 确定当前对象和指定对象表示的值是否相等。 |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | 确定当前对象和指定对象表示的值是否相等。 |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | 确定指定对象表示的值是否相等。 |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | 返回小于或等于指定值的最大整数值。 |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) 指定的 OLE 货币值为等效的 [Decimal](./) 值。未实现。 |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | 将指定的 [Decimal](./) 对象转换为其表示值的二进制表示形式。 |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) 指定的 [Decimal](./) 值为字节数组。 |
| int [GetHashCode](./gethashcode/)() const | 返回当前对象的哈希码。 |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | 获取对象类型代码。 |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | 将两个指定的 [Decimal](./) 值相乘。 |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | 返回一个新的 [Decimal](./) 类实例，该实例表示对指定对象表示的值取负后的结果。 |
| explicit [operator bool](./operator_bool/)() const | 将当前对象表示的值转换为布尔值。 |
| explicit [operator double](./operator_double/)() const | 将当前对象表示的值转换为双精度浮点数。 |
| explicit [operator float](./operator_float/)() const | 将当前对象表示的值转换为单精度浮点数。 |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | 确定当前对象和指定对象表示的值是否不相等。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 确定当前对象表示的值是否不等于 0。 |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | 返回一个新的 [Decimal](./) 类实例，该实例表示对当前对象和指定对象的值进行取模运算的结果。 |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | 将当前对象的值赋为对当前对象和指定对象的值进行取模运算的结果。 |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | 返回一个新的 [Decimal](./) 类实例，该实例表示对当前对象和指定对象的值进行乘法运算的结果。 |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | 将当前对象的值赋为对当前对象和指定对象的值进行乘法运算的结果。 |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | 返回一个新的 [Decimal](./) 类实例，该实例表示对当前对象和指定对象的值求和的结果。 |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | 递增当前对象表示的值。 |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | 将当前对象的值赋为对当前对象和指定对象的值求和的结果。 |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | 返回一个新的 [Decimal](./) 类实例，该实例表示用当前对象表示的值减去指定对象表示的值的结果。 |
| [Decimal](./) [operator-](./operator_minus/)() const | 返回一个新的 [Decimal](./) 类实例，该实例表示对当前对象的值取负的结果。 |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | 递减当前对象表示的值。 |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | 将当前对象的值赋为用当前对象的值减去指定对象的值的结果。 |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | 返回一个新的 [Decimal](./) 类实例，该实例表示用当前对象的值除以指定对象的值的结果。 |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | 将当前对象的值赋为用当前对象的值除以指定对象的值的结果。 |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | 确定当前对象表示的值是否小于指定对象表示的值。 |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | 确定当前对象表示的值是否小于或等于指定对象表示的值。 |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | 将指定对象表示的值赋给当前对象。 |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | 确定当前对象和指定对象表示的值是否相等。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 确定当前对象表示的值是否为 0。 |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | 确定当前对象表示的值是否大于指定对象表示的值。 |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | 确定当前对象表示的值是否大于或等于指定对象表示的值。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | 将十进制数的字符串表示转换为等效的 [Decimal](./) 类实例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | 使用指定的样式，将十进制数的字符串表示转换为等效的 [Decimal](./) 类实例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的格式提供程序，将十进制数的字符串表示转换为等效的 [Decimal](./) 类实例。 |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用指定的样式和格式提供程序，将十进制数的字符串表示转换为等效的 [Decimal](./) 类实例。 |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | 计算两个 [Decimal](./) 值相除后的余数。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | 将指定的值四舍五入到最近的整数。若指定值同等接近两个最近的整数，则通过参数指定函数的行为。 |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | 将指定的值四舍五入到具有指定小数位数的最近值。若指定值同等接近两个最近的值，则通过参数指定函数的行为。 |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | 从一个指定的 [Decimal](./) 值中减去另一个。 |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | 将 [Decimal](./) 值转换为无符号 8 位整数值。 |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | 将 [Decimal](./) 值转换为双精度浮点数。 |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | 将 [Decimal](./) 值转换为有符号 16 位整数值。 |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | 将 [Decimal](./) 值转换为有符号 32 位整数值。 |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | 将 [Decimal](./) 值转换为有符号 64 位整数值。 |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) 指定的 [Decimal](./) 值为等效的 OLE 货币值。未实现。 |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | 将 [Decimal](./) 值转换为有符号 8 位整数值。 |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | 将 [Decimal](./) 值转换为单精度浮点数。 |
| std::string [ToStdString](./tostdstring/)() const | 返回一个 std::string 实例，包含该对象表示的值的字符串表示形式。 |
| [String](../string/) [ToString](./tostring/)() const | 返回该对象表示的值的字符串表示形式。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用特定文化的格式信息将当前对象转换为字符串。 |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 使用指定的字符串格式和指定 [IFormatProvider](../iformatprovider/) 对象提供的特定文化的格式信息，将当前对象转换为其字符串表示形式。 |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | 返回该对象表示的值的字符串表示形式。供内部使用。 |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | 将 [Decimal](./) 值转换为无符号 16 位整数值。 |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | 将 [Decimal](./) 值转换为无符号 32 位整数值。 |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | 将 [Decimal](./) 值转换为无符号 64 位整数值。 |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | 返回 [Decimal](./) 对象，该对象表示一个值，其整数部分等于指定 [Decimal](./) 对象所表示值的整数部分，所有小数位被舍弃。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | 将包含数字字符串表示的指定字符串转换为等效的 [Decimal](./) 值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | 使用提供的格式信息和数字样式，将包含数字字符串表示的指定字符串转换为等效的 [Decimal](./) 值。 |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | 返回对 [TypeInfo](../typeinfo/) 对象的引用，该对象表示 [Decimal](./) 类的类型信息。 |
| [~Decimal](./~decimal/)() | 析构函数。 |

## 字段

| 字段 | 描述 |
| --- | --- |
| static [MaxValue](./maxvalue/) | 表示 [Decimal](./) 类能够表示的最大数字。 |
| static [MinusOne](./minusone/) | 表示数字 -1。 |
| static [MinValue](./minvalue/) | 表示 [Decimal](./) 类能够表示的最小数字。 |
| static [One](./one/) | 表示数字 1。 |
| static [Zero](./zero/) | 表示数字 0。 |

## 类型定义

| 类型别名 | 描述 |
| --- | --- |
| [number_type](./number_type/) | Detail::decimal_number_type 的别名。 |

## 备注



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
此代码示例产生以下输出:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## 另请参见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)