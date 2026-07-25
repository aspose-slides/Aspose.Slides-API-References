---
title: ToSByte()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された boolean 値を同等の 8 ビット符号付き整数に変換します。
type: docs
weight: 105
url: /ja/system/convert/tosbyte/
---
## Convert::ToSByte(bool) メソッド

指定された bool 値を同等の 8 ビット符号付き整数に変換します。

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) メソッド

指定された uint8_t を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) メソッド

指定された 8 ビット符号付き整数を返します。

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) メソッド

指定された uint16_t を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) メソッド

指定された uint32_t を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) メソッド

指定された uint64_t を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) メソッド

指定された float 数値を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) メソッド

指定された double 数値を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal&) メソッド

指定された Decimal の数値を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) メソッド

指定された Unicode 文字を同等の 8 ビット符号付き整数に変換します。

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) メソッド

指定された null 文字列を同等の 8 ビット整数値に変換します。

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```

### 戻り値

0。

## Convert::ToSByte(const char_t *) メソッド

数値の文字列表現を含む指定された c 文字列を同等の 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換する c 文字列 |

### 戻り値

指定された c 文字列が表す数値に等しい 8 ビット整数値

## Convert::ToSByte(const String&) メソッド

数値の文字列表現を含む指定された文字列を同等の 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

指定された文字列が表す数値に等しい 8 ビット整数値

## Convert::ToSByte(const String&, int) メソッド

指定された基数で表された数値の文字列表現を含む指定された文字列を同等の 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| from_base | int | 文字列が表す数値の基数 |

### 戻り値

指定された文字列が表す数値に等しい 8 ビット整数値

## Convert::ToSByte(const String&, const SharedPtr<IFormatProvider>&) メソッド

提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列の書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい符号なし 8 ビット整数値

## Convert::ToSByte(const String&, const SharedPtr<Globalization::CultureInfo>&) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String&, const SharedPtr<Globalization::NumberFormatInfo>&) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String&, std::nullptr_t) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&) メソッド

提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体のビットごとの組み合わせで、文字列が表す数値の許可されるスタイルを指定します |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列の書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい符号なし 8 ビット整数値

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) メソッド




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr<Object>&, const SharedPtr<IFormatProvider>&) メソッド

指定されたボックス化された値を同等の 8 ビット整数値に変換します。

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換する値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用する文字列書式 |

### 戻り値

指定されたボックス化された値に等しい 8 ビット整数値

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