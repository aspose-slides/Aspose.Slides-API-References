---
title: ToSingle()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の単精度浮動小数点数に変換します。
type: docs
weight: 209
url: /ja/system/convert/tosingle/
---
## Convert::ToSingle(bool) メソッド

指定されたブール値を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) メソッド

指定された float 値を返します。

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) メソッド

指定された倍精度数値を同等の単精度浮動小数点数に変換します。

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) メソッド

指定された十進数を同等の単精度浮動小数点数に変換します。

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) メソッド

指定された null 文字列を同等の単精度浮動小数点値に変換します。

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```

### 戻り値

0。

## Convert::ToSingle(const char_t *) メソッド

指定された数値表現文字列を含む c 文字列を同等の単精度浮動小数点値に変換します。

```cpp
static float System::Convert::ToSingle(const char_t *value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換する c 文字列 |

### 戻り値

指定された c 文字列が表す数値に等しい単精度浮動小数点値

## Convert::ToSingle(const String\&) メソッド

指定された数値表現文字列を含む文字列を同等の単精度浮動小数点値に変換します。

```cpp
static float System::Convert::ToSingle(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

指定された文字列が表す数値に等しい単精度浮動小数点値

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、指定された数値表現文字列を含む文字列を同等の単精度浮動小数点値に変換します。

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい単精度浮動小数点値

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報および数値スタイルを使用して、指定された数値表現文字列を含む文字列を同等の単精度浮動小数点値に変換します。

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体のビット単位の組み合わせで、文字列表現の許可されたスタイルを指定 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい単精度浮動小数点値

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を単精度浮動小数点値に変換します。

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換する値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列書式 |

### 戻り値

指定されたボックス化された値に等しい単精度浮動小数点値

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