---
title: ToChar()
second_title: Aspose.Slides for C++ API 參考文件
description: 不支援此轉換。始終拋出 InvalidCastException。
type: docs
weight: 118
url: /zh-hant/system/convert/tochar/
---
## Convert::ToChar(bool) 方法


不支援此轉換。始終拋出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) 方法


將指定的 8 位元無號整數轉換為等效的 Unicode 字元。

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) 方法


將指定的 8 位元有號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) 方法


將指定的 16 位元無號整數轉換為等效的 Unicode 字元。

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) 方法


將指定的 16 位元有號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) 方法


將指定的 32 位元無號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) 方法


將指定的 32 位元有號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) 方法


將指定的 64 位元無號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) 方法


將指定的 64 位元有號整數轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) 方法


不支援此轉換。始終拋出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) 方法


不支援此轉換。始終拋出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) 方法


不支援此轉換。始終拋出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) 方法


回傳指定的 Unicode 字元。

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) 方法


不支援此轉換。始終拋出 InvalidCastException。

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) 方法


將指定 C 字串的第一個且唯一的字元轉換為 char_t 值。

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 C 字串；預期該 C 字串僅有 1 個字元長度。 |

### 傳回值

如果指定的 C 字串恰好為 1 個字元長，則傳回其第一個且唯一的字元；否則傳回 0。

## Convert::ToChar(const String\&) 方法


將指定字串的第一個且唯一的字元轉換為 char_t 值。

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串；預期該字串恰好為 1 個字元長。 |

### 傳回值

如果指定的字串恰好為 1 個字元長，則傳回其第一個且唯一的字元；否則傳回 0。

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定字串的第一個且唯一的字元轉換為 char_t 值。

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串；預期該字串恰好為 1 個字元長。 |

### 傳回值

如果指定的字串恰好為 1 個字元長，則傳回其第一個且唯一的字元；否則傳回 0。

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的裝箱值轉換為等效的 Unicode 字元。

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向裝箱該欲轉換值之物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 若裝箱值的類型為 [String](../../string/) 時，要使用的字串格式 |

### 傳回值

與指定的裝箱值等效的 Unicode 字元。

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)