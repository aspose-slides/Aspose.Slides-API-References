---
title: ToInt32()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の 32 ビット符号付き整数に変換します。
type: docs
weight: 157
url: /ja/system/convert/toint32/
---
## Convert::ToInt32(bool) メソッド

指定されたブール値を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(bool value)
```

## Convert::ToInt32(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(uint8_t value)
```

## Convert::ToInt32(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(int8_t value)
```

## Convert::ToInt32(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(uint16_t value)
```

## Convert::ToInt32(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(int16_t value)
```

## Convert::ToInt32(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(uint32_t value)
```

## Convert::ToInt32(int32_t) メソッド

指定された 32 ビット符号付き整数を返します。

```cpp
static constexpr int System::Convert::ToInt32(int32_t value)
```

## Convert::ToInt32(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(uint64_t value)
```

## Convert::ToInt32(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(int64_t value)
```

## Convert::ToInt32(float) メソッド

指定された float 数値を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(float value)
```

## Convert::ToInt32(double) メソッド

指定された double 数値を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(double value)
```

## Convert::ToInt32(const Decimal\&) メソッド

指定された decimal 数値を同等の 32 ビット符号付き整数に変換します。

```cpp
static int System::Convert::ToInt32(const Decimal &value)
```

## Convert::ToInt32(char_t) メソッド

指定された Unicode 文字を同等の 32 ビット符号付き整数に変換します。

```cpp
static constexpr int System::Convert::ToInt32(char_t value)
```

## Convert::ToInt32(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static int System::Convert::ToInt32(DateTime value)
```

## Convert::ToInt32(std::nullptr_t) メソッド

指定された null 文字列を同等の 32 ビット整数値に変換します。

```cpp
static constexpr int System::Convert::ToInt32(std::nullptr_t)
```

### 戻り値

ゼロ。

## Convert::ToInt32(const char_t *) メソッド

数値の文字列表現を含む指定された C 文字列を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const char_t *value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換対象の C 文字列 |

### 戻り値

指定された C 文字列で表される数値に等しい 32 ビット整数値

## Convert::ToInt32(const String\&) メソッド

数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット整数値

## Convert::ToInt32(const String\&, int) メソッド

指定された基数で数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const String &value, int from_base)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| from_base | int | 文字列が表す数値の基数 |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット整数値

## Convert::ToInt32(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット整数値

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, std::nullptr_t) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, std::nullptr_t)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位組み合わせで、数値文字列の許容スタイルを指定します |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット整数値

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt32(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static int System::Convert::ToInt32(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt32(Enum) メソッド




```cpp
template<typename Enum,typename> static int32_t System::Convert::ToInt32(Enum value)
```

## Convert::ToInt32(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を同等の 32 ビット整数値に変換します。

```cpp
static int System::Convert::ToInt32(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列書式 |

### 戻り値

指定されたボックス化された値に等しい 32 ビット整数値

## 参考

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)