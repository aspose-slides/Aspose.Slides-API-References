---
title: ToInt16()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の 16 ビット符号付き整数に変換します。
type: docs
weight: 131
url: /ja/system/convert/toint16/
---
## Convert::ToInt16(bool) メソッド

指定されたブール値を同等の 16 ビット符号付き整数に変換します。

```cpp
static constexpr int16_t System::Convert::ToInt16(bool value)
```

## Convert::ToInt16(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static constexpr int16_t System::Convert::ToInt16(uint8_t value)
```

## Convert::ToInt16(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static constexpr int16_t System::Convert::ToInt16(int8_t value)
```

## Convert::ToInt16(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(uint16_t value)
```

## Convert::ToInt16(int16_t) メソッド

指定された 16 ビット符号付き整数を返します。

```cpp
static constexpr int16_t System::Convert::ToInt16(int16_t value)
```

## Convert::ToInt16(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(uint32_t value)
```

## Convert::ToInt16(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(int32_t value)
```

## Convert::ToInt16(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(uint64_t value)
```

## Convert::ToInt16(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(int64_t value)
```

## Convert::ToInt16(float) メソッド

指定された float 値を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(float value)
```

## Convert::ToInt16(double) メソッド

指定された double 値を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(double value)
```

## Convert::ToInt16(const Decimal\&) メソッド

指定された decimal 値を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(const Decimal &value)
```

## Convert::ToInt16(char_t) メソッド

指定された unicode 文字を同等の 16 ビット符号付き整数に変換します。

```cpp
static int16_t System::Convert::ToInt16(char_t value)
```

## Convert::ToInt16(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static int16_t System::Convert::ToInt16(DateTime value)
```

## Convert::ToInt16(std::nullptr_t) メソッド

指定された null 文字列を同等の 16 ビット整数値に変換します。

```cpp
static constexpr int16_t System::Convert::ToInt16(std::nullptr_t)
```

### 戻り値

0。

## Convert::ToInt16(const char_t *) メソッド

数値の文字列表現を含む指定された c 文字列を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換対象の c 文字列 |

### 戻り値

指定された c 文字列が表す数値に等しい 16 ビット整数値

## Convert::ToInt16(const String\&) メソッド

数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |

### 戻り値

指定された文字列が表す数値に等しい 16 ビット整数値

## Convert::ToInt16(const String\&, int) メソッド

指定された基数で表された数値の文字列表現を含む文字列を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const String &value, int from_base)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| from_base | int | 文字列が表す数値の基数 |

### 戻り値

指定された文字列が表す数値に等しい 16 ビット整数値

## Convert::ToInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい 16 ビット整数値

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static int16_t System::Convert::ToInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, std::nullptr_t) メソッド




```cpp
static int16_t System::Convert::ToInt16(const String &value, std::nullptr_t)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位の組み合わせで、数値文字列の許可されるスタイルを指定します |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい 16 ビット整数値

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド 




```cpp
static int16_t System::Convert::ToInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToInt16(Enum) メソッド 




```cpp
template<typename Enum,typename> static int16_t System::Convert::ToInt16(Enum value)
```

## Convert::ToInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を同等の 16 ビット整数値に変換します。

```cpp
static int16_t System::Convert::ToInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用する文字列書式 |

### 戻り値

指定されたボックス化された値に相当する 16 ビット整数値

## 参照

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