---
title: String
second_title: Aspose.Slides for C++ API 參考
description: "String 類別在整個函式庫中使用。它在轉譯程式碼時取代 C# 的 System.String。由於最佳化原因，它不被視為 Object 的子類別。此類型應在堆疊上分配，並以值或參考傳遞給函式。絕不要使用 System::SmartPtr 類別來管理此類型的物件。"
type: docs
weight: 1275
url: /zh-hant/system/string/
---
## String 類別

[String](./) 類別在整個程式庫中使用。是 C# [System.String](./) 在翻譯程式碼時的替代方案。出於最佳化原因，並未視為 [Object](../object/) 的子類別。此類型應分配於堆疊上，並以值或引用傳遞給函式。切勿使用 [System::SmartPtr](../smartptr/) 類別來管理此類型的物件。

```cpp
class String
```

## 方法

| Method | Description |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) 是 C++ 端的值類型，會隱式（無繼承）實作某些介面。 |
| const UChar * [begin](./begin/)() const | 傳回指向實際字串緩衝區開頭的指標。永不重新配置任何記憶體。並不保證緩衝區以 null 結尾。 |
| [String](./) [Clone](./clone/)() const | 建立目前字串的副本。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | 比較兩個子字串的大小（小於、等於、大於）。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 比較兩個子字串的大小（小於、等於、大於）。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 比較兩個字串的大小（小於、等於、大於）。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | 比較兩個字串的大小（小於、等於、大於）。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | 比較兩個字串的大小（小於、等於、大於）。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 比較兩個字串的大小（小於、等於、大於）。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | 以序數模式比較兩個字串的大小（小於、等於、大於）。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | 以序數模式比較兩個字串的大小（小於、等於、大於）。 |
| int [CompareTo](./compareto/)(const [String](./)\&) const | 以「小於、等於、大於」的方式比較兩個字串。使用目前的文化設定。 |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | 串接字串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | 串接字串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | 串接字串。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | 串接字串。 |
| **bool** [Contains](./contains/)(const [String](./)\&) const | 檢查 str 是否為目前字串的子字串。 |
| **bool** [Contains](./contains/)(char16_t) const | 檢查字串是否包含給定的字符。 |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | 建立字串的副本。 |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | 將字串字元複製到現有的陣列元素中。不會執行重新調整大小。 |
| const UChar * [end](./end/)() const | 傳回指向實際字串緩衝區結尾的指標。永不重新配置任何記憶體。並不保證緩衝區以 null 結尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | 檢查字串是否以指定的子字串結尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 檢查字串是否以指定的子字串結尾。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 檢查字串是否以指定的子字串結尾。 |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) 等價比較。支援由 StringComparison 列舉提供的多種模式。 |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) 等價比較。使用 [System::StringComparison::Ordinal](../stringcomparison/) 比較模式。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | 以序數比較模式檢查兩個字串相等。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 比較兩個字串是否相等。 |
| int [FastToAscii](./fasttoascii/)(char, int) const | 嘗試將 [String](./) 轉換為 ASCII 字串。 |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | 以 C# 風格格式化字串。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | 以 C# 風格格式化字串。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | 以 C# 風格格式化字串。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | 以 C# 風格格式化字串。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | 以 C# 風格格式化字串。 |
| static [String](./) [FromAscii](./fromascii/)(const char *) | 從 ASCII 字串建立 [String](./)。 |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | 從 ASCII 字串建立 [String](./)。 |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | 從 ASCII 字串建立 [String](./)。 |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | 從 utf16 字串建立 [String](./)。 |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | 從 utf32 字串建立 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | 從 utf8 字串建立 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | 從 utf8 字串建立 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | 從 utf8 字串建立 [String](./)。 |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | 從 utf8 字串建立 [String](./)。 |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | 從寬字串建立 [String](./)。 |
| int [get_Length](./get_length/)() const | 取得字串長度。 |
| int [GetHashCode](./gethashcode/)() const | 對字串內容產生雜湊值。以 ICU 實作，與 C# 的雜湊值不同。 |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 子字串向前搜尋。 |
| int [IndexOf](./indexof/)(char_t, int) const | 字元向前搜尋。 |
| int [IndexOf](./indexof/)(char_t, int, int) const | 在子字串中進行字元向前搜尋。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | 子字串向前搜尋。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 子字串向前搜尋。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | 子字串向前搜尋。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | 子字串向前搜尋。 |
| int [IndexOfAny](./indexofany/)(char_t, int) const | 字元向前搜尋。 |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | 依序在此字串中搜尋 str 的所有字符。若找到第一個字符，回傳其位置；若未找到，則搜尋下一個字符，依此類推。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 在整個字串中搜尋任意傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，若不匹配則比較第二個字符，依此類推。回傳第一個匹配目標字符的索引。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 在子字串中搜尋任意傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，若不匹配則比較第二個字符，依此類推。回傳第一個匹配目標字符的索引。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 在子字串中搜尋任意傳入的字符。將字串的第一個字符與 anyOf 中的所有字符比較，若不匹配則比較第二個字符，依此類推。回傳第一個匹配目標字符的索引。 |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | 在指定位置插入子字串。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | 檢查字串物件是否為 [TypeInfo](../typeinfo/) 指定的類型。 |
| **bool** [IsAsciiString](./isasciistring/)() const | 表示 [String](./) 是否僅包含 ASCII 符號。 |
| **bool** [IsEmpty](./isempty/)() const | 檢查字串是否同時非 null 且為空。 |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 檢查 Unicode 字串是否已使用指定的正規化形式正規化。 |
| **bool** [IsNull](./isnull/)() const | 檢查字串是否被視為 null。[String](./) 為 null，且僅在透過 [String()](./string/) 建構子、移動、從 null 字串複製或指派，或呼叫 [reset()](./reset/) 方法時為 null。 |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | 檢查字串是否為空或被視為 null。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | 檢查傳入的字串是否為 null 或空。 |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | 表示指定的字串是否為 null、空，或僅包含空白字元。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | 使用字串作為分隔符號來連接陣列。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | 使用字串作為分隔符號來連接陣列。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | 使用字串作為分隔符號來連接陣列。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | 使用字串作為分隔符號來連接陣列。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | 子字串向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 子字串向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | 子字串向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | 子字串向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(char_t) const | 字元向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | 字元向後搜尋。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | 字元向後搜尋。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 自字串尾端向前搜尋任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，若不匹配則比較前一個字符，依此類推。回傳第一個找到的匹配之索引。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | 在子字串中向後搜尋任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，若不匹配則比較前一個字符，依此類推。回傳第一個找到的匹配之索引。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | 在子字串中向後搜尋任意傳入的字符。將字串最後一個字符與 anyOf 中的所有字符比較，若不匹配則比較前一個字符，依此類推。回傳第一個找到的匹配之索引。 |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 使用指定的正規化形式正規化 Unicode 字串。 |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | 將字串轉換為唯讀 span。 |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | 不等於比較運算子。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 檢查字串是否非 null。使用與 [IsNull()](./isnull/) 相同的邏輯。 |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) 串接運算子。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) 與字串常量或字符字串指標的串接。 |
| [String](./) [operator+](./operator_plus/)(char_t) const | 在字串末端加入字符。 |
| [String](./) [operator+](./operator_plus/)(int) const | 在字串末端加入整數值的字串表示。 |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | 在字串末端加入無號整數值的字串表示。 |
| [String](./) [operator+](./operator_plus/)(**double**) const | 在字串末端加入浮點數值的字串表示。 |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | 在字串末端加入整數值的字串表示。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 在字串末端加入參照型別物件的字串表示。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 在字串末端加入參照型別物件的字串表示。 |
| [String](./) [operator+](./operator_plus/)(T) const | 在字串末端加入布林值的字串表示。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | 串接賦值運算子。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | 串接賦值運算子。 |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | 比較字串的順序。 |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | 指派運算子。 |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | 移動指派運算子。 |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | 等值比較運算子。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 檢查字串是否為 null。使用與 [IsNull()](./isnull/) 呼叫相同的邏輯。 |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | 比較字串的順序。 |
| char_t [operator[]](./operator[]/)(int) const | 取得指定位置的字元。 |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | 在原始字串左側加入填充。 |
| [String](./) [PadRight](./padright/)(int, char_t) const | 在原始字串右側加入填充。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | 傳回實際字串緩衝區最後一個字元（若有）的反向迭代器。 |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | 從目前字串中擷取除子字串外的所有內容。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | 傳回實際字串緩衝區第一個字元之前的反向迭代器（若有）。 |
| [String](./) [Replace](./replace/)(char_t, char_t) const | 取代字串中所有出現的字元。 |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | 取代此字串中所有出現的搜尋項目。 |
| [String](./)\& [reset](./reset/)() | 將字串設為 null。相當於 C# 中的 'string_variable_name = null'。 |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | 設定指定位置的字元。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | 以字元分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 以字元分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | 以兩個字元之一分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 以指定的字元之一分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 以指定的字元之一分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | 以子字串分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 以子字串分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 以子字串分割字串。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | 以子字串分割字串。目前僅支援零或一個元素的分隔符陣列。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | 檢查字串是否以指定的子字串開頭。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 檢查字串是否以指定的子字串開頭。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 檢查字串是否以指定的子字串開頭。 |
|  [String](./string/)() | 預設建構子。建立被視為 null 的字串物件。 |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | 根據字串常值建構字串。將常值視為以 null 結尾的字串，根據常值大小計算目標字串長度。 |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | 根據字元字串指標建構字串。將指向的字串視為以 null 結尾，根據 null 字元計算目標字串長度。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | 根據字串常值建構字串。將常值視為 UTF8 的 null 結尾字串，根據常值大小計算目標字串長度。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | 根據字元字串指標建構字串。將指向的字串視為 UTF8 的 null 結尾，根據 null 字元計算目標字串長度。 |
|  [String](./string/)(const char16_t *, int) | 根據字元字串指標與明確長度建構字串。 |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | 初始化 [System.String](./) 類別的新實例，以指定的唯讀 span 所指示的 Unicode 字元。 |
|  [String](./string/)(const char *, int) | 根據字元字串指標與明確長度建構字串。 |
|  [String](./string/)(const char16_t *, int, int) | 根據字元字串指標從起始位置使用長度建構字串。 |
| explicit  [String](./string/)(const char16_t, int) | 填充建構子。 |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | nullptr 建構子。宣告為模板以解決與其他模板建構子的優先順序。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | 根據寬字串常值建構字串。將常值視為以 null 結尾的字串，根據常值大小計算目標字串長度。從 **wchar_t** 的轉換在某些平台上耗時，因此不允許隱式轉換。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | 根據寬字元字串指標建構字串。將指向的字串視為以 null 結尾，根據 null 字元計算目標字串長度。從 **wchar_t** 的轉換在某些平台上耗時，因此不允許隱式轉換。 |
| explicit  [String](./string/)(const **wchar_t** *, int) | 根據寬字元字串指標與明確長度建構字串。從 **wchar_t** 的轉換在某些平台上耗時，因此不允許隱式轉換。 |
| explicit  [String](./string/)(const **wchar_t**, int) | 填充建構子。從 **wchar_t** 的轉換在某些平台上耗時，因此不允許隱式轉換。 |
|  [String](./string/)(const [String](./)\&) | 拷貝建構子。 |
|  [String](./string/)([String](./)\&&) | 移動建構子。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | 將整個字元陣列轉換為字串。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | 將字元陣列子範圍轉換為字串。若參數超出陣列範圍，將建構空字串。 |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | 將 UnicodeString 包裝成 [String](./)。 |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | 移動建構子。 |
| explicit  [String](./string/)(const std::wstring\&) | 從寬字串建立 [String](./)。 |
| explicit  [String](./string/)(const std::u16string\&) | 從 utf16 字串建立 [String](./)。 |
| explicit  [String](./string/)(const std::string\&) | 從 UTF-8 格式的 std::string 建立 [String](./)。 |
| explicit  [String](./string/)(const std::u32string\&) | 從 std::u32string 建立 [String](./)。 |
| [String](./) [Substring](./substring/)(**int32_t**) const | 擷取子字串。 |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | 擷取子字串。 |
| std::string [ToAsciiString](./toasciistring/)() const | 將字串轉換為 std::string。使用 ASCII 編碼。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | 將字串或子字串轉換為位元組陣列。 |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | 將字串或子字串轉換為字元陣列。 |
| [String](./) [ToLower](./tolower/)() const | 將所有字串字元轉換為小寫。 |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用特定文化將所有字串字元轉換為小寫。 |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | 使用不變文化將所有字串字元轉換為小寫。 |
| [String](./) [ToString](./tostring/)() const | 在對值類型物件呼叫 [ToString()](./tostring/) 的情境中，處理 [String](./) 類別的封裝器。 |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | 在對值類型物件呼叫 [ToString()](./tostring/) 的情境中，處理 [String](./) 類別的封裝器。 |
| std::u16string [ToU16Str](./tou16str/)() const | 將字串轉換為 std::u16string。 |
| std::u32string [ToU32Str](./tou32str/)() const | 將字串轉換為 std::u32string。 |
| [String](./) [ToUpper](./toupper/)() const | 將所有字串字元轉換為大寫。 |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 使用特定文化將所有字串字元轉換為大寫。 |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | 使用不變文化將所有字串字元轉換為大寫。 |
| std::string [ToUtf8String](./toutf8string/)() const | 將字串轉換為 std::string。使用 UTF-8 編碼。 |
| std::wstring [ToWCS](./towcs/)() const | 將字串轉換為 std::wstring。 |
| [String](./) [Trim](./trim/)() const | 從字串的開頭與結尾移除所有空白字元。 |
| [String](./) [Trim](./trim/)(char_t) const | 從字串的開頭與結尾移除傳入字元的所有出現。 |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | 從字串的開頭與結尾移除傳入字元集合的所有出現。 |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 從字串的開頭與結尾移除傳入字元集合的所有出現。 |
| [String](./) [TrimEnd](./trimend/)() const | 從字串結尾移除所有空白字元。 |
| [String](./) [TrimEnd](./trimend/)(char_t) const | 從字串結尾移除傳入字元的所有出現。 |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | 從字串結尾移除傳入字元集合的所有出現。 |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 從字串結尾移除傳入字元集合的所有出現。 |
| [String](./) [TrimStart](./trimstart/)() const | 從字串開頭移除所有空白字元。 |
| [String](./) [TrimStart](./trimstart/)(char_t) const | 從字串開頭移除傳入字元的所有出現。 |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | 從字串開頭移除傳入字元集合的所有出現。 |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 從字串開頭移除傳入字元集合的所有出現。 |
| const UChar * [u_str](./u_str/)() const | 傳回 ICU 風格的 null 結尾緩衝區。可能會重新配置字串。 |
|  [~String](./~string/)() | 解構子。 |

## Fields

| 欄位 | 說明 |
| --- | --- |
| static [Empty](./empty/) | 空字串。 |
| static [Null](./null/) | Null 字串。 |

## Typedefs

| 型別別名 | 說明 |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | 反向迭代器類型。 |

## 備註



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // 從字符陣列構造字串並列印它。
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // 從位元組陣列構造字串並列印它。
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // 修剪下面的字串並列印它。
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // 列印 . 中的單詞數。
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
此程式碼範例產生以下輸出：
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)