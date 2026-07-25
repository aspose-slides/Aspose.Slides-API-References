---
title: ToDouble()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の倍精度浮動小数点数に変換します。
type: docs
weight: 222
url: /ja/system/convert/todouble/
---
## Convert::ToDouble(bool) メソッド

指定されたブール値を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) メソッド

指定された単精度数を同等の倍精度浮動小数点数に変換します。

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) メソッド

指定された double を返します。

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) メソッド

指定された十進数を同等の倍精度浮動小数点数に変換します。

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) メソッド

変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) メソッド

指定された null 文字列を同等の倍精度浮動小数点値に変換します。

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```

### 戻り値

ゼロ。

## Convert::ToDouble(const char_t *) メソッド

数値の文字列表現を含む c 文字列を同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Convert::ToDouble(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換対象の c 文字列 |

### 戻り値

指定された c 文字列が表す数値と等しい倍精度浮動小数点値

## Convert::ToDouble(const String\&) メソッド

数値の文字列表現を含む文字列を同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Convert::ToDouble(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |

### 戻り値

指定された文字列が表す数値と等しい倍精度浮動小数点値

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、数値の文字列表現を含む文字列を同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値と等しい倍精度浮動小数点値

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報および数値スタイルを使用して、数値の文字列表現を含む文字列を同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体のビット単位組み合わせで、文字列表現に許可されるスタイルを指定 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値と等しい倍精度浮動小数点値

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

ボックス化された値を倍精度浮動小数点値に変換します。ボックス化された値の型が [String](../../string/) の場合、指定された文字列書式が変換に使用されます。

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列書式 |

### 戻り値

指定されたボックス化された値に等しい倍精度浮動小数点値

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
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)