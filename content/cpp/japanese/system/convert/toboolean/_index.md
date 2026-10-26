---
title: ToBoolean()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された boolean 値を返します。
type: docs
weight: 79
url: /ja/system/convert/toboolean/
---
## Convert::ToBoolean(bool) メソッド

指定された boolean 値を返します。

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```
## Convert::ToBoolean(uint8_t) メソッド

指定された 8 ビット符号なし整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```
## Convert::ToBoolean(int8_t) メソッド

指定された 8 ビット符号付き整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```
## Convert::ToBoolean(uint16_t) メソッド

指定された 16 ビット符号なし整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```
## Convert::ToBoolean(int16_t) メソッド

指定された 16 ビット符号付き整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```
## Convert::ToBoolean(uint32_t) メソッド

指定された 32 ビット符号なし整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```
## Convert::ToBoolean(int32_t) メソッド

指定された 32 ビット符号付き整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```
## Convert::ToBoolean(uint64_t) メソッド

指定された 64 ビット符号なし整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```
## Convert::ToBoolean(int64_t) メソッド

指定された 64 ビット符号付き整数を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```
## Convert::ToBoolean(float) メソッド

指定された float 数値を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```
## Convert::ToBoolean(double) メソッド

指定された double 数値を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```
## Convert::ToBoolean(const Decimal\&) メソッド

指定された decimal 数値を同等の boolean 値に変換します。

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```
## Convert::ToBoolean(char_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static bool System::Convert::ToBoolean(char_t value)
```
## Convert::ToBoolean(DateTime) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```
## Convert::ToBoolean(std::nullptr_t) メソッド

指定された null 文字列を同等の boolean 値に変換します。

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### 戻り値

false。

## Convert::ToBoolean(const char_t *) メソッド

指定された c-string を bool 型の値に変換します。

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | 変換する c-string |

### 戻り値

"True" と等しい場合は true、"False" と等しい場合は false を返します。

## Convert::ToBoolean(const String\&) メソッド

指定された文字列を bool 型の値に変換します。

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

"True" と等しい場合は true、"False" と等しい場合は false を返します。

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列を bool 型の値に変換します。

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

"True" と等しい場合は true、"False" と等しい場合は false を返します。

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定されたボックス化された値を同等の boolean 値に変換します。

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換する値をボックス化しているオブジェクトへの SharedPtr |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列書式 |

### 戻り値

指定されたボックス化された値に相当する boolean 値

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)