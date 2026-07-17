---
title: String
second_title: Aspose.Slides for C++ API 参考
description: "String 类在整个库中使用。它是将 C# System.String 转换为代码时的替代方案。出于优化原因，它不被视为 Object 子类。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 System::SmartPtr 类来管理此类型的对象。"
type: docs
weight: 1249
url: /zh/system/string/
---
## String 类


[String](./) 类在整个库中使用。它是将 C# [System.String](./) 转换为代码时的替代方案。出于优化原因，它不被视为 [Object](../object/) 的子类。此类型应在栈上分配，并通过值或引用传递给函数。切勿使用 [System::SmartPtr](../smartptr/) 类来管理此类型的对象。

```cpp
class String
```

## 方法

| 方法 | 描述 |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) 是 C++ 端的值类型，隐式（无继承）实现了一些接口。 |
| const UChar * [begin](./begin/)() const | 返回指向实际字符串缓冲区起始位置的指针。永不重新分配任何内容。不能保证缓冲区以空字符结尾。 |
| [String](./) [Clone](./clone/)() const | 创建当前字符串的副本。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | 对两个子字符串进行小于等于大于比较。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 对两个子字符串进行小于等于大于比较。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 对两个字符串进行小于等于大于比较。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | 对两个字符串进行小于等于大于比较。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | 对两个字符串进行小于等于大于比较。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 对两个字符串进行小于等于大于比较。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | 使用序数模式对两个字符串进行小于等于大于比较。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | 使用序数模式对两个字符串进行小于等于大于比较。 |
| int [CompareTo](./compareto/)(const [String](./)\&) const | 以“小于等于更多”方式比较两个字符串。使用当前文化。 |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | 连接字符串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | 连接字符串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | 连接字符串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | 连接字符串。 |
| **bool** [Contains](./contains/)(const [String](./)\&) const | 检查 str 是否为当前字符串的子串。 |
| **bool** [Contains](./contains/)(char16_t) const | 检查字符串是否包含给定字符。 |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | 创建字符串副本。 |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | 将字符串字符复制到现有数组元素中。不会进行重新大小调整。 |
| const UChar * [end](./end/)() const | 返回指向实际字符串缓冲区末尾的指针。永不重新分配任何内容。不能保证缓冲区以空字符结尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | 检查字符串是否以指定子串结尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 检查字符串是否以指定子串结尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 检查字符串是否以指定子串结尾。 |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) 相等比较。支持 StringComparison 枚举提供的多种模式。 |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) 相等比较。使用 [System::StringComparison::Ordinal](../stringcomparison/) 比较模式。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | 使用序数比较模式对两个字符串进行等价比较。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 对两个字符串进行等价比较。 |
| int [FastToAscii](./fasttoascii/)(char, int) const | 尝试将 [String](./) 转换为 ASCII 字符串。 |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | 以 C# 风格格式化字符串。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | 以 C# 风格格式化字符串。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | 以 C# 风格格式化字符串。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | 以 C# 风格格式化字符串。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | 以 C# 风格格式化字符串。 |
| static [String](./) [FromAscii](./fromascii/)(const char *) | 从 ASCII 字符串创建 [String](./)。 |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | 从 ASCII 字符串创建 [String](./)。 |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | 从 ASCII 字符串创建 [String](./)。 |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | 从 utf16 字符串创建 [String](./)。 |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | 从 utf32 字符串创建 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | 从 utf8 字符串创建 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | 从 utf8 字符串创建 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | 从 utf8 字符串创建 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | 从 utf8 字符串创建 [String](./)。 |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | 从宽字符字符串创建 [String](./)。 |
| int [get_Length](./get_length/)() const | 获取字符串长度。 |
| int [GetHashCode](./gethashcode/)() const | 对包含的字符串进行哈希。实现于 ICU，哈希值与 C# 不匹配。 |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 前向子串查找。 |
| int [IndexOf](./indexof/)(char_t, int) const | 前向字符查找。 |
| int [IndexOf](./indexof/)(char_t, int, int) const | 在子串中前向字符查找。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | 前向子串查找。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 前向子串查找。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | 前向子串查找。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | 前向子串查找。 |
| int [IndexOfAny](./indexofany/)(char_t, int) const | 前向字符查找。 |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | 依次在此字符串中查找 str 的所有字符。如果找到第一个字符则返回其位置，否则继续查找第二个字符，依此类推。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 在整个字符串中查找任意传入字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的索引。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 在子串中查找任意传入字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的索引。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 在子串中查找任意传入字符。将字符串的第一个字符与 anyOf 中的所有字符比较，然后比较第二个字符，依此类推。返回第一个匹配任意目标字符的索引。 |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | 在指定位置插入子串。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 检查字符串对象是否为 [TypeInfo](../typeinfo/) 指定的类型。 |
| **bool** [IsAsciiString](./isasciistring/)() const | 指示 [String](./) 是否仅包含 ASCII 符号。 |
| **bool** [IsEmpty](./isempty/)() const | 检查字符串是否既非 null 又为空。 |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 检查 Unicode 字符串是否使用指定的正规化形式进行正规化。 |
| **bool** [IsNull](./isnull/)() const | 检查字符串是否被视为 null。[String](./) 为 null，仅在通过 [String()](./string/) 构造函数、移动、从 null 字符串复制或赋值，或调用 [reset()](./reset/) 方法时为 null。 |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | 检查字符串是否为空或被视为 null。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | 检查传入的字符串是否为 null 或空。 |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | 指示指定的字符串是否为 null、空或仅由空白字符组成。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | 使用字符串作为分隔符连接数组。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | 使用字符串作为分隔符连接数组。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | 使用字符串作为分隔符连接数组。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | 使用字符串作为分隔符连接数组。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | 后向子串查找。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 后向子串查找。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 后向子串查找。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | 后向子串查找。 |
| int [LastIndexOf](./lastindexof/)(char_t) const | 后向字符查找。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | 后向字符查找。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | 后向字符查找。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 在整个字符串中向后查找任意传入字符。将字符串的最后一个字符与 anyOf 中的所有字符比较，然后比较前一个字符，依此类推。返回首次匹配的索引。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 在子串中向后查找任意传入字符。将字符串的最后一个字符与 anyOf 中的所有字符比较，然后比较前一个字符，依此类推。返回首次匹配的索引。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 在子串中向后查找任意传入字符。将字符串的最后一个字符与 anyOf 中的所有字符比较，然后比较前一个字符，依此类推。返回首次匹配的索引。 |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 使用指定的正规化形式对 Unicode 字符串进行正规化。 |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | 将字符串转换为只读 span。 |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | 非相等比较运算符。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 检查字符串是否不为 null。逻辑与 [IsNull()](./isnull/) 调用相同。 |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) 连接运算符。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 使用字符串文字或字符字符串指针进行 [String](./) 连接。 |
| [String](./) [operator+](./operator_plus/)(char_t) const | 将字符添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(int) const | 将整数值的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | 将无符号整数值的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(**double**) const | 将浮点数值的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | 将整数值的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 将引用类型对象的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 将引用类型对象的字符串表示添加到字符串末尾。 |
| [String](./) [operator+](./operator_plus/)(T) const | 将布尔值的字符串表示添加到字符串末尾。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | 连接赋值运算符。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | 连接赋值运算符。 |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | 对字符串进行顺序比较。 |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | 赋值运算符。 |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | 移动赋值运算符。 |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | 相等比较运算符。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 检查字符串是否为 null。逻辑与 [IsNull()](./isnull/) 调用相同。 |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | 对字符串进行顺序比较。 |
| char_t [operator[]](./operator[]/)(int) const | 获取指定位置的字符。 |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | 在原始字符串左侧添加填充。 |
| [String](./) [PadRight](./padright/)(int, char_t) const | 在原始字符串右侧添加填充。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | 返回指向实际字符串缓冲区最后一个字符（如果有）的逆向迭代器。 |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | 从当前字符串中提取除指定子串之外的全部内容。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | 返回指向实际字符串缓冲区第一个字符之前位置的逆向迭代器（如果有）。 |
| [String](./) [Replace](./replace/)(char_t, char_t) const | 替换字符串中所有出现的指定字符。 |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | 替换字符串中所有出现的查找内容。 |
| [String](./)\& [reset](./reset/)() | 将字符串设为 null。相当于 C# 中的 `string_variable_name = null`。 |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | 设置指定位置的字符。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | 按字符分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 按字符分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | 按两个字符中的任意一个分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 按指定字符集合分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 按指定字符集合分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | 按子串分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 按子串分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 按子串分割字符串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 按子串分割字符串。当前仅支持零或一个元素的分隔符数组。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | 检查字符串是否以指定子串开头。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 检查字符串是否以指定子串开头。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 检查字符串是否以指定子串开头。 |
|  [String](./string/)() | 默认构造函数。创建被视为 null 的字符串对象。 |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | 基于字符串文字构造字符串。将文字视为以空字符结尾的字符串，依据文字大小计算目标字符串长度。 |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | 基于字符字符串指针构造字符串。将指向的字符串视为以空字符结尾，依据空字符计算目标字符串长度。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | 基于字符串文字构造字符串。将文字视为 UTF8 编码的以空字符结尾的字符串，依据文字大小计算目标字符串长度。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | 基于字符字符串指针构造字符串。将指向的字符串视为 UTF8 编码的以空字符结尾的字符串，依据空字符计算目标字符串长度。 |
|  [String](./string/)(const char16_t *, int) | 基于字符字符串指针和显式长度构造字符串。 |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | 使用指定只读 span 中的 Unicode 字符初始化 [System.String](./) 类的新实例。 |
|  [String](./string/)(const char *, int) | 基于字符字符串指针和显式长度构造字符串。 |
|  [String](./string/)(const char16_t *, int, int) | 基于字符字符串指针和起始位置以及长度构造字符串。 |
| explicit  [String](./string/)(const char16_t, int) | 填充构造函数。 |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | 空指针构造函数。声明为模板以解决与其他模板构造函数的优先级冲突。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | 基于宽字符文字构造字符串。将文字视为以空字符结尾的字符串，依据文字大小计算目标字符串长度。**wchar_t** 的转换在某些平台上耗时较长，因而不允许隐式转换。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | 基于宽字符字符串指针构造字符串。将指向的字符串视为以空字符结尾，依据空字符计算目标字符串长度。**wchar_t** 的转换在某些平台上耗时较长，因而不允许隐式转换。 |
| explicit  [String](./string/)(const **wchar_t** *, int) | 基于宽字符字符串指针和显式长度构造字符串。**wchar_t** 的转换在某些平台上耗时较长，因而不允许隐式转换。 |
| explicit  [String](./string/)(const **wchar_t**, int) | 填充构造函数。**wchar_t** 的转换在某些平台上耗时较长，因而不允许隐式转换。 |
|  [String](./string/)(const [String](./)\&) | 拷贝构造函数。 |
|  [String](./string/)([String](./)\&&) | 移动构造函数。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | 将整个字符数组转换为字符串。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | 将字符数组子范围转换为字符串。如果参数超出数组边界，则构造空字符串。 |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | 将 UnicodeString 包装为 [String](./)。 |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | 移动构造函数。 |
| explicit  [String](./string/)(const std::wstring\&) | 从宽字符字符串创建 [String](./)。 |
| explicit  [String](./string/)(const std::u16string\&) | 从 utf16 字符串创建 [String](./)。 |
| explicit  [String](./string/)(const std::string\&) | 从 UTF-8 编码的 std::string 创建 [String](./)。 |
| explicit  [String](./string/)(const std::u32string\&) | 从 std::u32string 创建 [String](./)。 |
| [String](./) [Substring](./substring/)(**int32_t**) const | 提取子串。 |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | 提取子串。 |
| std::string [ToAsciiString](./toasciistring/)() const | 将字符串转换为 std::string。使用 ASCII 编码。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | 将字符串或子串转换为字节数组。 |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | 将字符串或子串转换为字符数组。 |
| [String](./) [ToLower](./tolower/)() const | 将字符串的所有字符转换为小写。 |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用特定文化将字符串的所有字符转换为小写。 |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | 使用不变文化将字符串的所有字符转换为小写。 |
| [String](./) [ToString](./tostring/)() const | 在对值类型对象调用 [ToString()](./tostring/) 时，处理 [String](./) 类的包装器。 |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 在对值类型对象调用 [ToString()](./tostring/) 时，处理 [String](./) 类的包装器。 |
| std::u16string [ToU16Str](./tou16str/)() const | 将字符串转换为 std::u16string。 |
| std::u32string [ToU32Str](./tou32str/)() const | 将字符串转换为 std::u32string。 |
| [String](./) [ToUpper](./toupper/)() const | 将字符串的所有字符转换为大写。 |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用特定文化将字符串的所有字符转换为大写。 |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | 使用不变文化将字符串的所有字符转换为大写。 |
| std::string [ToUtf8String](./toutf8string/)() const | 将字符串转换为 std::string。使用 UTF-8 编码。 |
| std::wstring [ToWCS](./towcs/)() const | 将字符串转换为 std::wstring。 |
| [String](./) [Trim](./trim/)() const | 删除字符串两端的所有空白字符。 |
| [String](./) [Trim](./trim/)(char_t) const | 删除字符串两端所有出现的指定字符。 |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | 删除字符串两端所有出现的指定字符集合。 |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 删除字符串两端所有出现的指定字符集合。 |
| [String](./) [TrimEnd](./trimend/)() const | 删除字符串末尾的所有空白字符。 |
| [String](./) [TrimEnd](./trimend/)(char_t) const | 删除字符串末尾所有出现的指定字符。 |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | 删除字符串末尾所有出现的指定字符集合。 |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 删除字符串末尾所有出现的指定字符集合。 |
| [String](./) [TrimStart](./trimstart/)() const | 删除字符串开头的所有空白字符。 |
| [String](./) [TrimStart](./trimstart/)(char_t) const | 删除字符串开头所有出现的指定字符。 |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | 删除字符串开头所有出现的指定字符集合。 |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 删除字符串开头所有出现的指定字符集合。 |
| const UChar * [u_str](./u_str/)() const | 返回 ICU 样式的以空字符结尾的缓冲区。可能会重新分配字符串。 |
|  [~String](./~string/)() | 析构函数。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| static [Empty](./empty/) | 空字符串。 |
| static [Null](./null/) | 空（null）字符串。 |
## 类型别名

| 类型别名 | 描述 |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器类型。 |
## 备注



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // 从字符数组构造字符串并打印它。
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // 从字节数组构造字符串并打印它。
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // 修剪下面的字符串并打印它。
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // 打印字符串中的单词数。
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
此代码示例产生以下输出：
hello
world
"This string contains whitespaces in the beginning and at the end."
单词数: 11
*/
```

## 另见

* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)