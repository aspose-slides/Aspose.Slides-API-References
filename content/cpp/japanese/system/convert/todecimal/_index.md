---
title: ToDecimal()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたブール値を同等の十進数に変換します。
type: docs
weight: 235
url: /ja/system/convert/todecimal/
---
## Convert::ToDecimal(bool) method

指定されたブール値を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) method

指定された8ビット符号なし整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) method

指定された8ビット符号付き整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) method

指定された16ビット符号なし整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) method

指定された16ビット符号付き整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) method

指定された32ビット符号なし整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) method

指定された32ビット符号付き整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) method

指定された64ビット符号なし整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) method

指定された64ビット符号付き整数を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) method

指定されたfloat型の数値を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) method

指定されたdouble型の数値を同等の十進数に変換します。

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) method

指定された十進数を返します。

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) method

変換はサポートされていません。常にInvalidCastExceptionがスローされます。

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) method

変換はサポートされていません。常にInvalidCastExceptionがスローされます。

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) method

指定されたnull文字列を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```

### 戻り値

Zero.

## Convert::ToDecimal(const char_t *) method

指定された文字列（数値の文字列表現）を含むc文字列を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換対象のc文字列 |

### 戻り値

指定されたc文字列が表す数値に等しい[Decimal](../../decimal/)値

## Convert::ToDecimal(const String\&) method

指定された文字列（数値の文字列表現）を含む文字列を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |

### 戻り値

指定された文字列が表す数値に等しい[Decimal](../../decimal/)値

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) method

提供された書式情報を使用して、指定された文字列（数値の文字列表現）を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい[Decimal](../../decimal/)値

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method

指定された数値スタイルと書式情報を使用して、指定された文字列（数値の文字列表現）を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles列挙体のビット単位の組み合わせで、数値表現文字列の許容スタイルを指定 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す数値に等しい[Decimal](../../decimal/)値

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method

指定されたボックス化された値を同等の[Decimal](../../decimal/)値に変換します。

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が[String](../../string/)の場合に使用する文字列書式 |

### 戻り値

指定されたボックス化された値に等しい[Decimal](../../decimal/)値

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)