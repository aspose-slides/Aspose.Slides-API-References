---
title: ToUInt64()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の 64 ビット符号なし整数に変換します。
type: docs
weight: 196
url: /ja/system/convert/touint64/
---
## Convert::ToUInt64(bool) メソッド

指定された bool 値を同等の 64 ビット符号なし整数に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(bool value)
```

## Convert::ToUInt64(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint8_t value)
```

## Convert::ToUInt64(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(int8_t value)
```

## Convert::ToUInt64(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint16_t value)
```

## Convert::ToUInt64(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(int16_t value)
```

## Convert::ToUInt64(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint32_t value)
```

## Convert::ToUInt64(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(int32_t value)
```

## Convert::ToUInt64(uint64_t) メソッド

指定された 64 ビット符号なし整数を返します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(uint64_t value)
```

## Convert::ToUInt64(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(int64_t value)
```

## Convert::ToUInt64(float) メソッド

指定された float 数値を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(float value)
```

## Convert::ToUInt64(double) メソッド

指定された double 数値を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(double value)
```

## Convert::ToUInt64(const Decimal\&) メソッド

指定された decimal 数値を同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const Decimal &value)
```

## Convert::ToUInt64(char_t) メソッド

指定された Unicode 文字を同等の 64 ビット符号なし整数に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(char_t value)
```

## Convert::ToUInt64(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static uint64_t System::Convert::ToUInt64(DateTime value)
```

## Convert::ToUInt64(std::nullptr_t) メソッド

指定された null-string を同等の符号なし 64 ビット整数値に変換します。

```cpp
static constexpr uint64_t System::Convert::ToUInt64(std::nullptr_t)
```

### 戻り値

0。

## Convert::ToUInt64(const char_t *) メソッド

数値の文字列表現を含む指定された c-string を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const char_t *value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換対象の c-string |

### 戻り値

指定された c-string が表す数値に等しい符号なし 64 ビット整数値

## Convert::ToUInt64(const String\&) メソッド

数値の文字列表現を含む指定された文字列を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |

### 戻り値

指定された文字列が表す数値に等しい符号なし 64 ビット整数値

## Convert::ToUInt64(const String\&, int) メソッド

指定された基数で表された数値の文字列表現を含む指定された文字列を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, int from_base)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| from_base | int | 文字列が表す数値の基数 |

### 戻り値

指定された文字列が表す数値に等しい符号なし 64 ビット整数値

## Convert::ToUInt64(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、指定された文字列を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい符号なし 64 ビット整数値

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, std::nullptr_t) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, std::nullptr_t)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報と数値スタイルを使用して、指定された文字列を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位の組み合わせで、数値の文字列表現に許可されるスタイルを指定します |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい符号なし 64 ビット整数値

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt64(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド

```cpp
static uint64_t System::Convert::ToUInt64(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt64(Enum) メソッド

```cpp
template<typename Enum,typename> static uint64_t System::Convert::ToUInt64(Enum value)
```

## Convert::ToUInt64(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を同等の符号なし 64 ビット整数値に変換します。

```cpp
static uint64_t System::Convert::ToUInt64(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列書式 |

### 戻り値

指定されたボックス化された値に等しい符号なし 64 ビット整数値

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* typedef [SharedPtr](../../sharedptr/)
* クラス [Decimal](../../decimal/)
* クラス [DateTime](../../datetime/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* クラス [Object](../../object/)
* 構造体 [Convert](../)
* 構造体 [Enum](../../enum/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)