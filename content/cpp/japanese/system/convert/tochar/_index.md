---
title: ToChar()
second_title: Aspose.Slides for C++ API リファレンス
description: 変換はサポートされていません。常に InvalidCastException がスローされます。
type: docs
weight: 118
url: /ja/system/convert/tochar/
---
## Convert::ToChar(bool) メソッド


変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) メソッド


指定された 8 ビット符号なし整数を同等の Unicode 文字に変換します。

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) メソッド


指定された 8 ビット符号あり整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) メソッド


指定された 16 ビット符号なし整数を同等の Unicode 文字に変換します。

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) メソッド


指定された 16 ビット符号あり整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) メソッド


指定された 32 ビット符号なし整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) メソッド


指定された 32 ビット符号あり整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) メソッド


指定された 64 ビット符号なし整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) メソッド


指定された 64 ビット符号あり整数を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) メソッド


変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) メソッド


変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) メソッド


変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) メソッド


指定された Unicode 文字を返します。

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) メソッド


変換はサポートされていません。常に InvalidCastException がスローされます。

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) メソッド


指定された C 文字列の最初で唯一の文字を char_t 値に変換します。

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const char_t * | 変換する c-string。c-string は正確に 1 文字であることが期待されます。 |

### 戻り値

指定された c-string が正確に 1 文字である場合、その最初かつ唯一の文字を返します。それ以外の場合は 0 を返します。

## Convert::ToChar(const String\&) メソッド


指定された文字列の最初で唯一の文字を char_t 値に変換します。

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。文字列は正確に 1 文字であることが期待されます。 |

### 戻り値

指定された文字列が正確に 1 文字である場合、その最初かつ唯一の文字を返します。それ以外の場合は 0 を返します。

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド


指定された文字列の最初で唯一の文字を char_t 値に変換します。

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。文字列は正確に 1 文字であることが期待されます。 |

### 戻り値

指定された文字列が正確に 1 文字である場合、その最初かつ唯一の文字を返します。それ以外の場合は 0 を返します。

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) メソッド


ボックス化された値を同等の Unicode 文字に変換します。

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換対象の値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用される文字列フォーマット |

### 戻り値

指定されたボックス化された値に相当する Unicode 文字

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