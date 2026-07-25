---
title: ToByte()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の 8 ビット符号なし整数に変換します。
type: docs
weight: 92
url: /ja/system/convert/tobyte/
---
## Convert::ToByte(bool) メソッド

指定されたブール値を同等の 8 ビット符号なし整数に変換します。

```cpp
static constexpr uint8_t System::Convert::ToByte(bool value)
```

## Convert::ToByte(uint8_t) メソッド

指定された 8 ビット符号なし整数を返します。

```cpp
static constexpr uint8_t System::Convert::ToByte(uint8_t value)
```

## Convert::ToByte(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(int8_t value)
```

## Convert::ToByte(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(uint16_t value)
```

## Convert::ToByte(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(int16_t value)
```

## Convert::ToByte(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(uint32_t value)
```

## Convert::ToByte(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(int32_t value)
```

## Convert::ToByte(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(uint64_t value)
```

## Convert::ToByte(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(int64_t value)
```

## Convert::ToByte(float) メソッド

指定された float 数値を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(float value)
```

## Convert::ToByte(double) メソッド

指定された double 数値を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(double value)
```

## Convert::ToByte(const Decimal\&) メソッド

指定された decimal 数値を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(const Decimal &value)
```

## Convert::ToByte(char_t) メソッド

指定された Unicode 文字を同等の 8 ビット符号なし整数に変換します。

```cpp
static uint8_t System::Convert::ToByte(char_t value)
```

## Convert::ToByte(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static uint8_t System::Convert::ToByte(DateTime value)
```

## Convert::ToByte(std::nullptr_t) メソッド

指定された null 文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static constexpr uint8_t System::Convert::ToByte(std::nullptr_t)
```

### 戻り値

ゼロ。

## Convert::ToByte(const char_t *) メソッド

数値の文字列表現を含む指定された C 文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const char_t *value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | 変換する C 文字列 |

### 戻り値

指定された C 文字列で表された数値に等しい符号なし 8 ビット整数値

## Convert::ToByte(const String\&) メソッド

数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const String &value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

指定された文字列で表された数値に等しい符号なし 8 ビット整数値

## Convert::ToByte(const String\&, int) メソッド

指定された基数で表された数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const String &value, int from_base)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| from_base | int | 文字列で表される数値の基数 |

### 戻り値

指定された文字列で表された数値に等しい符号なし 8 ビット整数値

## Convert::ToByte(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報を使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列で表された数値に等しい符号なし 8 ビット整数値

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, std::nullptr_t) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, std::nullptr_t)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

提供された書式情報と数値スタイルを使用して、数値の文字列表現を含む指定された文字列を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位の組み合わせで、数値の文字列表現に許可されたスタイルを指定します |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列で表された数値に等しい符号なし 8 ビット整数値

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToByte(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static uint8_t System::Convert::ToByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToByte(Enum) メソッド




```cpp
template<typename Enum,typename> static uint8_t System::Convert::ToByte(Enum value)
```

## Convert::ToByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を同等の符号なし 8 ビット整数値に変換します。

```cpp
static uint8_t System::Convert::ToByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換する値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用する文字列書式 |

### 戻り値

指定されたボックス化された値に等しい符号なし 8 ビット整数値

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
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