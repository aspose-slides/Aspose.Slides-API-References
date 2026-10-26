---
title: String
second_title: Aspose.Slides for C++ API リファレンス
description: "ライブラリ全体で使用される String クラスです。コード変換時に C# の System.String の代替として使用されます。最適化の観点から、Object のサブクラスとはみなされません。この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。この型のオブジェクトを管理するために System::SmartPtr クラスを使用しないでください。"
type: docs
weight: 1275
url: /ja/system/string/
---
## String クラス


[String](./) クラスはライブラリ全体で使用されます。 C# [System.String](./) の代替としてコードを変換する際に使用されます。 最適化の観点から、[Object](../object/) のサブクラスとはみなされません。 この型はスタック上に割り当て、値渡しまたは参照渡しで関数に渡すべきです。 [System::SmartPtr](../smartptr/) クラスを使用してこの型のオブジェクトを管理しないでください。

```cpp
class String
```

## メソッド

| メソッド | 説明 |
| --- | --- |
|  [ASPOSECPP_VALUE_TYPE_IMPLEMENTS_INTERFACES](./asposecpp_value_type_implements_interfaces/)() | [String](./) は C++ 側の値型で、暗黙的に（継承なしで）いくつかのインターフェイスを実装します。 |
| const UChar * [begin](./begin/)() const | 実際の文字列バッファの先頭へのポインタを返します。何も再割り当てしません。バッファがヌル終端であることは保証しません。 |
| [String](./) [Clone](./clone/)() const | 現在の文字列のコピーを作成します。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**) | 二つのサブストリングを大小比較します。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 二つのサブストリングを大小比較します。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 二つの文字列を大小比較します。 |
| static int [Compare](./compare/)(const [String](./)\&, int, const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) | 二つの文字列を大小比較します。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**) | 二つの文字列を大小比較します。 |
| static int [Compare](./compare/)(const [String](./)\&, const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) | 二つの文字列を大小比較します。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, const [String](./)\&) | 順序モードを使用して二つの文字列を大小比較します。 |
| static int [CompareOrdinal](./compareordinal/)(const [String](./)\&, int, const [String](./)\&, int, int) | 順序モードを使用して二つの文字列を大小比較します。 |
| int [CompareTo](./compareto/)(const [String](./)\&) const | 二つの文字列を「less-equals-more」スタイルで比較します。現在のカルチャを使用します。 |
| static [String](./) [Concat](./concat/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&) | 文字列を連結します。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&) | 文字列を連結します。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&) | 文字列を連結します。 |
| static [String](./) [Concat](./concat/)(const [String](./)\&, const [String](./)\&, const [String](./)\&, const [String](./)\&) | 文字列を連結します。 |
| **bool** [Contains](./contains/)(const [String](./)\&) const | 文字列が現在の文字列のサブストリングであるかをチェックします。 |
| **bool** [Contains](./contains/)(char16_t) const | 文字列が指定された文字を含むかをチェックします。 |
| static [String](./) [Copy](./copy/)(const [String](./)\&) | 文字列のコピーを作成します。 |
| void [CopyTo](./copyto/)(int, const [ArrayPtr](../arrayptr/)\<char_t\>\&, int, int) const | 文字列の文字を既存の配列要素にコピーします。サイズ変更は行われません。 |
| const UChar * [end](./end/)() const | 実際の文字列バッファの末尾へのポインタを返します。何も再割り当てしません。バッファがヌル終端であることは保証しません。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&) const | 文字列が指定されたサブストリングで終わるかをチェックします。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 文字列が指定されたサブストリングで終わるかをチェックします。 |
| **bool** [EndsWith](./endswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 文字列が指定されたサブストリングで終わるかをチェックします。 |
| **bool** [Equals](./equals/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | [String](./) の等価比較です。StringComparison 列挙体が提供する複数のモードがサポートされています。 |
| **bool** [Equals](./equals/)(const [String](./)\&) const | [String](./) の等価比較です。[System::StringComparison::Ordinal](../stringcomparison/) 比較モードを使用します。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&) | Ordinal 比較モードを使用して二つの文字列を等価比較します。 |
| static **bool** [Equals](./equals/)(const [String](./)\&, const [String](./)\&, [System::StringComparison](../stringcomparison/)) | 二つの文字列を等価比較します。 |
| int [FastToAscii](./fasttoascii/)(char, int) const | [String](./) を ASCII 文字列に変換しようとします。 |
| static [String](./) [Format](./format/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, const [String](./)\&, const Args\&...) | C# スタイルで文字列をフォーマットします。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const [String](./)\&, const Args\&...) | C# スタイルで文字列をフォーマットします。 |
| static [String](./) [Format](./format/)(std::nullptr_t, const char16_t(&), const Args\&...) | C# スタイルで文字列をフォーマットします。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const Args\&...) | C# スタイルで文字列をフォーマットします。 |
| static [String](./) [Format](./format/)(const [String](./)\&, const [System::ArrayPtr](../arrayptr/)\<T\>\&) | C# スタイルで文字列をフォーマットします。 |
| static [String](./) [FromAscii](./fromascii/)(const char *) | ASCII 文字列から [String](./) を作成します。 |
| static [String](./) [FromAscii](./fromascii/)(const char *, int) | ASCII 文字列から [String](./) を作成します。 |
| static [String](./) [FromAscii](./fromascii/)(const std::string\&) | ASCII 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf16](./fromutf16/)(const std::u16string\&) | utf16 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf32](./fromutf32/)(const **uint32_t** *, **int32_t**) | utf32 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *) | utf8 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf8](./fromutf8/)(const char *, int) | utf8 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf8](./fromutf8/)(const **uint8_t** *) | utf8 文字列から [String](./) を作成します。 |
| static [String](./) [FromUtf8](./fromutf8/)(const std::string\&) | utf8 文字列から [String](./) を作成します。 |
| static [String](./) [FromWCS](./fromwcs/)(const std::wstring\&) | widestring から [String](./) を作成します。 |
| int [get_Length](./get_length/)() const | 文字列の長さを取得します。 |
| int [GetHashCode](./gethashcode/)() const | 文字列のハッシュを計算します。ICU で実装されており、C# のハッシュとは一致しません。 |
| int [IndexOf](./indexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | サブストリングの前方検索を行います。 |
| int [IndexOf](./indexof/)(char_t, int) const | 文字の前方検索を行います。 |
| int [IndexOf](./indexof/)(char_t, int, int) const | サブストリング内で文字の前方検索を行います。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int) const | サブストリングの前方検索を行います。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | サブストリングの前方検索を行います。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int, [System::StringComparison](../stringcomparison/)) const | サブストリングの前方検索を行います。 |
| int [IndexOf](./indexof/)(const [String](./)\&, int, int) const | サブストリングの前方検索を行います。 |
| int [IndexOfAny](./indexofany/)(char_t, int) const | 文字の前方検索を行います。 |
| int [IndexOfAny](./indexofany/)(const [String](./)\&, int) const | 文字列内のすべての文字を順に検索します。最初の文字が見つかればその位置を返し、見つからなければ次の文字を検索し、というように続きます。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 渡された文字のいずれかを文字列全体で検索します。最初の文字を anyOf のすべての文字と比較し、次に二番目の文字を比較するという順序で行います。対象文字のいずれかに一致した最初の文字のインデックスを返します。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | サブストリング内で渡された文字のいずれかを検索します。最初の文字を anyOf のすべての文字と比較し、次に二番目の文字を比較するという順序で行います。対象文字のいずれかに一致した最初の文字のインデックスを返します。 |
| int [IndexOfAny](./indexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | サブストリング内で渡された文字のいずれかを検索します。最初の文字を anyOf のすべての文字と比較し、次に二番目の文字を比較するという順序で行います。対象文字のいずれかに一致した最初の文字のインデックスを返します。 |
| [String](./) [Insert](./insert/)(int, const [String](./)\&) const | 指定した位置にサブストリングを挿入します。 |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | [TypeInfo](../typeinfo/) で指定された型の文字列オブジェクトかどうかをチェックします。 |
| **bool** [IsAsciiString](./isasciistring/)() const | [String](./) が ASCII 記号のみを含むかどうかを示します。 |
| **bool** [IsEmpty](./isempty/)() const | 文字列が非 null かつ空であるかをチェックします。 |
| **bool** [IsNormalized](./isnormalized/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 指定された正規化形式を使用して Unicode 文字列が正規化されているかをチェックします。 |
| **bool** [IsNull](./isnull/)() const | 文字列が null と見なされるかをチェックします。[String](./) は、[String()](./string/) コンストラクタで構築された場合、または null 文字列からムーブ、コピー、代入された場合、もしくは [reset()](./reset/) メソッドが呼び出された場合にのみ null です。 |
| **bool** [IsNullOrEmpty](./isnullorempty/)() const | 文字列が空か、null と見なされるかをチェックします。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [String](./)\&) | 渡された文字列が null か空であるかをチェックします。 |
| static **bool** [IsNullOrWhiteSpace](./isnullorwhitespace/)(const [String](./)\&) | 指定された文字列が null、空、または空白文字のみで構成されているかどうかを示します。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, int) | 文字列を区切り文字として配列を結合します。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const System::Details::ArrayView\<[String](./)\>\&, int, int) | 文字列を区切り文字として配列を結合します。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[String](./)\>\>\&) | 文字列を区切り文字として配列を結合します。 |
| static [String](./) [Join](./join/)(const [String](./)\&, const [ArrayPtr](../arrayptr/)\<[SharedPtr](../sharedptr/)\<[Object](../object/)\>\>\&) | 文字列を区切り文字として配列を結合します。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int) const | サブストリングの後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | サブストリングの後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, [System::StringComparison](../stringcomparison/)) const | サブストリングの後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(const [String](./)\&, int, int, [StringComparison](../stringcomparison/)) const | サブストリングの後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(char_t) const | 文字の後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**) const | 文字の後方検索を行います。 |
| int [LastIndexOf](./lastindexof/)(char_t, **int32_t**, **int32_t**) const | 文字の後方検索を行います。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 渡された文字のいずれかを文字列全体で逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較するという順序で行います。最初に見つかった一致のインデックスを返します。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**) const | サブストリング内で渡された文字のいずれかを逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較するという順序で行います。最初に見つかった一致のインデックスを返します。 |
| int [LastIndexOfAny](./lastindexofany/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) const | サブストリング内で渡された文字のいずれかを逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較するという順序で行います。最初に見つかった一致のインデックスを返します。 |
| [String](./) [Normalize](./normalize/)([System::Text::NormalizationForm](../../system.text/normalizationform/)) const | 指定された正規化形式を使用して Unicode 文字列を正規化します。 |
|  [operator ReadOnlySpan< char16_t >](./operator_readonlyspan_less_char16_t__greater/)() const | 文字列を読み取り専用スパンに変換します。 |
| **bool** [operator!=](./operator_not_equal/)(const [String](./)\&) const | 非等価比較演算子です。 |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | 文字列が null でないかをチェックします。[IsNull()](./isnull/) 呼び出しと同じロジックを適用します。 |
| [String](./) [operator+](./operator_plus/)(const [String](./)\&) const | [String](./) 連結演算子です。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | [String](./) 文字列リテラルまたは文字列ポインタとの連結です。 |
| [String](./) [operator+](./operator_plus/)(char_t) const | 文字列の末尾に文字を追加します。 |
| [String](./) [operator+](./operator_plus/)(int) const | 整数値の文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(**uint32_t**) const | 符号なし整数値の文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(**double**) const | 浮動小数点値の文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(**int64_t**) const | 整数値の文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 参照型オブジェクトの文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(const T\&) const | 参照型オブジェクトの文字列表現を文字列の末尾に追加します。 |
| [String](./) [operator+](./operator_plus/)(T) const | ブール値の文字列表現を文字列の末尾に追加します。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(char_t) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(const [String](./)\&) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**double**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint8_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int16_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint16_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int32_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint32_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**int64_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(**uint64_t**) | 連結代入演算子です。 |
| [String](./)\& [operator+=](./operator_plus_equal/)(T) | 連結代入演算子です。 |
| **bool** [operator<](./operator_less/)(const [String](./)\&) const | 文字列を順序比較します。 |
| [String](./)\& [operator=](./operator_equal/)(const [String](./)\&) | 代入演算子です。 |
| [String](./)\& [operator=](./operator_equal/)([String](./)\&&) | ムーブ代入演算子です。 |
| **bool** [operator==](./operator_equal_equal/)(const [String](./)\&) const | 等価比較演算子です。 |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | 文字列が null かどうかをチェックします。[IsNull()](./isnull/) 呼び出しと同じロジックが適用されます。 |
| **bool** [operator>](./operator_greater/)(const [String](./)\&) const | 文字列を順序比較します。 |
| char_t [operator[]](./operator[]/)(int) const | 指定された位置の文字を取得します。 |
| [String](./) [PadLeft](./padleft/)(int, char_t) const | 元の文字列の左側にパディングを追加します。 |
| [String](./) [PadRight](./padright/)(int, char_t) const | 元の文字列の右側にパディングを追加します。 |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() const | 実際の文字列バッファの最後の文字への逆イテレータを返します（存在する場合）。 |
| [String](./) [Remove](./remove/)(**int32_t**, **int32_t**) const | 現在の文字列からサブ文字列以外のすべてを抽出します。 |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() const | 実際の文字列バッファの最初の文字の前への逆イテレータを返します（存在する場合）。 |
| [String](./) [Replace](./replace/)(char_t, char_t) const | 文字列中の文字のすべての出現箇所を置換します。 |
| [String](./) [Replace](./replace/)(const [String](./)\&, const [String](./)\&) const | この文字列中の検索対象のすべての出現箇所を置換します。 |
| [String](./)\& [reset](./reset/)() | 文字列を null に設定します。C# の 'string_variable_name = null' と同等です。 |
| [String](./)\& [SetCharAt](./setcharat/)(int, char_t) | 指定された位置に文字を設定します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, [StringSplitOptions](../stringsplitoptions/)) const | 文字で文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 文字で文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(char_t, char_t, [StringSplitOptions](../stringsplitoptions/)) const | 2 つの文字のいずれかで文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, [StringSplitOptions](../stringsplitoptions/)) const | 指定された文字のいずれかで文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, [StringSplitOptions](../stringsplitoptions/)) const | 指定された文字のいずれかで文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, [StringSplitOptions](../stringsplitoptions/)) const | サブ文字列で文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [String](./)\&, int, [StringSplitOptions](../stringsplitoptions/)) const | サブ文字列で文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, [StringSplitOptions](../stringsplitoptions/)) const | サブ文字列で文字列を分割します。 |
| [ArrayPtr](../arrayptr/)\<[String](./)\> [Split](./split/)(const [ArrayPtr](../arrayptr/)\<[String](./)\>\&, int, [StringSplitOptions](../stringsplitoptions/)) const | サブ文字列で文字列を分割します。現在、区切り文字配列は 0 または 1 の要素のみサポートしています。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&) const | 文字列が指定されたサブ文字列で始まるかチェックします。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, [System::StringComparison](../stringcomparison/)) const | 文字列が指定されたサブ文字列で始まるかチェックします。 |
| **bool** [StartsWith](./startswith/)(const [String](./)\&, **bool**, const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 文字列が指定されたサブ文字列で始まるかチェックします。 |
|  [String](./string/)() | デフォルトコンストラクタ。null とみなされる文字列オブジェクトを作成します。 |
|  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char16_t\>::value\>::type *) | 文字列リテラルに基づいて文字列を構築します。リテラルを null 終端文字列と見なし、リテラルサイズに基づいて対象文字列の長さを計算します。 |
|  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char16_t\>::value\>::type *) | 文字列ポインタに基づいて文字列を構築します。指す文字列を null 終端とみなし、null 文字に基づいて対象文字列の長さを計算します。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, char\>::value\>::type *) | UTF8 の文字列リテラルに基づいて文字列を構築します。リテラルを UTF8 の null 終端文字列と見なし、リテラルサイズに基づいて対象文字列の長さを計算します。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, char\>::value\>::type *) | UTF8 の文字列ポインタに基づいて文字列を構築します。指す文字列を UTF8 の null 終端と見なし、null 文字に基づいて対象文字列の長さを計算します。 |
|  [String](./string/)(const char16_t *, int) | 文字列ポインタと明示的な長さから文字列を構築します。 |
|  [String](./string/)(const [ReadOnlySpan](../readonlyspan/)\<char16_t\>\&) | 指定された読み取り専用スパンで示された Unicode 文字で [System.String](./) クラスの新しいインスタンスを初期化します。 |
|  [String](./string/)(const char *, int) | 文字列ポインタと明示的な長さから文字列を構築します。 |
|  [String](./string/)(const char16_t *, int, int) | 開始位置から長さを使用して文字列ポインタから文字列を構築します。 |
| explicit  [String](./string/)(const char16_t, int) | フィルコンストラクタです。 |
|  [String](./string/)(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) | nullptr コンストラクタ。他のテンプレートコンストラクタとの優先順位を解決するためにテンプレートとして宣言されています。 |
| explicit  [String](./string/)(T\&, typename std::enable_if\<[IsStringLiteral](../isstringliteral/)\<T, **wchar_t**\>::value\>::type *) | ワイド文字列リテラルに基づいて文字列を構築します。リテラルを null 終端文字列と見なし、リテラルサイズに基づいて対象文字列の長さを計算します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されていません。 |
| explicit  [String](./string/)(const T\&, typename std::enable_if\<[IsStringPointer](../isstringpointer/)\<T, **wchar_t**\>::value\>::type *) | 文字列ポインタに基づいて文字列を構築します。指す文字列を null 終端と見なし、null 文字に基づいて対象文字列の長さを計算します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されていません。 |
| explicit  [String](./string/)(const **wchar_t** *, int) | ワイド文字列ポインタと明示的な長さから文字列を構築します。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されていません。 |
| explicit  [String](./string/)(const **wchar_t**, int) | フィルコンストラクタです。**wchar_t** からの変換は一部のプラットフォームで時間がかかるため、暗黙的な変換は許可されていません。 |
|  [String](./string/)(const [String](./)\&) | コピーコンストラクタです。 |
|  [String](./string/)([String](./)\&&) | ムーブコンストラクタです。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&) | 全体の文字配列を文字列に変換します。 |
|  [String](./string/)(const [ArrayPtr](../arrayptr/)\<char16_t\>\&, int, int) | 文字配列のサブレンジを文字列に変換します。パラメータが配列の範囲外の場合、空文字列が構築されます。 |
| explicit  [String](./string/)(const codeporting_icu::UnicodeString\&) | UnicodeString を [String](./) にラップします。 |
| explicit  [String](./string/)(codeporting_icu::UnicodeString\&&) | ムーブコンストラクタです。 |
| explicit  [String](./string/)(const std::wstring\&) | ワイド文字列から [String](./) を作成します。 |
| explicit  [String](./string/)(const std::u16string\&) | utf16 文字列から [String](./) を作成します。 |
| explicit  [String](./string/)(const std::string\&) | UTF-8 形式で表現された std::string 文字列から [String](./) を作成します。 |
| explicit  [String](./string/)(const std::u32string\&) | std::u32string 文字列から [String](./) を作成します。 |
| [String](./) [Substring](./substring/)(**int32_t**) const | サブ文字列を抽出します。 |
| [String](./) [Substring](./substring/)(**int32_t**, **int32_t**) const | サブ文字列を抽出します。 |
| std::string [ToAsciiString](./toasciistring/)() const | 文字列を std::string に変換します。ASCII エンコードを使用します。 |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)(**int32_t**, **int32_t**, **bool**) const | 文字列またはサブ文字列をバイト配列に変換します。 |
| [ArrayPtr](../arrayptr/)\<char_t\> [ToCharArray](./tochararray/)(**int32_t**, **int32_t**) const | 文字列またはサブ文字列を文字配列に変換します。 |
| [String](./) [ToLower](./tolower/)() const | 文字列のすべての文字を小文字に変換します。 |
| [String](./) [ToLower](./tolower/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 特定のカルチャーを使用して文字列のすべての文字を小文字に変換します。 |
| [String](./) [ToLowerInvariant](./tolowerinvariant/)() const | 不変カルチャーを使用して文字列のすべての文字を小文字に変換します。 |
| [String](./) [ToString](./tostring/)() const | [String](./) クラスを、[ToString()](./tostring/) が値型オブジェクトで呼び出されるコンテキストで扱うためのラッパーです。 |
| [String](./) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | [String](./) クラスを、[ToString()](./tostring/) が値型オブジェクトで呼び出されるコンテキストで扱うためのラッパーです。 |
| std::u16string [ToU16Str](./tou16str/)() const | 文字列を std::u16string に変換します。 |
| std::u32string [ToU32Str](./tou32str/)() const | 文字列を std::u32string に変換します。 |
| [String](./) [ToUpper](./toupper/)() const | 文字列のすべての文字を大文字に変換します。 |
| [String](./) [ToUpper](./toupper/)(const [SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | 特定のカルチャーを使用して文字列のすべての文字を大文字に変換します。 |
| [String](./) [ToUpperInvariant](./toupperinvariant/)() const | 不変カルチャーを使用して文字列のすべての文字を大文字に変換します。 |
| std::string [ToUtf8String](./toutf8string/)() const | 文字列を std::string に変換します。UTF-8 エンコードを使用します。 |
| std::wstring [ToWCS](./towcs/)() const | 文字列を std::wstring に変換します。 |
| [String](./) [Trim](./trim/)() const | 文字列の先頭と末尾からすべての空白文字を削除します。 |
| [String](./) [Trim](./trim/)(char_t) const | 文字列の先頭と末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [Trim](./trim/)(const [String](./)\&) const | 文字列の先頭と末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [Trim](./trim/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 文字列の先頭と末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimEnd](./trimend/)() const | 文字列の末尾からすべての空白文字を削除します。 |
| [String](./) [TrimEnd](./trimend/)(char_t) const | 文字列の末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimEnd](./trimend/)(const [String](./)\&) const | 文字列の末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimEnd](./trimend/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 文字列の末尾から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimStart](./trimstart/)() const | 文字列の先頭からすべての空白文字を削除します。 |
| [String](./) [TrimStart](./trimstart/)(char_t) const | 文字列の先頭から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimStart](./trimstart/)(const [String](./)\&) const | 文字列の先頭から渡された文字のすべての出現箇所を削除します。 |
| [String](./) [TrimStart](./trimstart/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) const | 文字列の先頭から渡された文字のすべての出現箇所を削除します。 |
| const UChar * [u_str](./u_str/)() const | ICU 形式の null 終端バッファを返します。文字列が再割り当てされる可能性があります。 |
|  [~String](./~string/)() | デストラクタです。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| static [Empty](./empty/) | 空文字列です。 |
| static [Null](./null/) | null 文字列です。 |
## 型エイリアス

| 型エイリアス | 説明 |
| --- | --- |
| [reverse_iterator](./reverse_iterator/) | 逆イテレータ型です。 |
## 備考



```cpp
#include "system/string.h"
#include <iostream>

int main()
{
  // 文字配列から文字列を構築し、出力します。
  const auto chars = {u'h', u'e', u'l', u'l', u'o'};
  const System::String string1(chars);
  std::cout << string1 << std::endl;

  // バイト配列から文字列を構築し、出力します。
  const uint8_t bytes[] = {0x77, 0x6f, 0x72, 0x6c, 0x64, 0x0};
  const auto string2 = System::String::FromUtf8(bytes);
  std::cout << string2 << std::endl;

  // 以下の文字列の前後空白を除去して出力します。
  const System::String string3(u"   This string contains whitespaces in the beginning and at the end.   ");
  std::cout << '"' << string3.Trim() << '"' << std::endl;

  // 文中の単語数を出力します。
  std::cout << "Number of words: " << string3.Trim().Split(' ')->get_Length() << std::endl;

  return 0;
}
/*
このコード例は以下の出力を生成します:
hello
world
"This string contains whitespaces in the beginning and at the end."
Number of words: 11
*/
```

## 参照

* 名前空間 [System](../)
* ライブラリ [Aspose.Slides](../../)