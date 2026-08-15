---
title: ToBoolean()
second_title: Aspose.Slides for C++ API 參考
description: 傳回指定的布林值。
type: docs
weight: 79
url: /zh-hant/system/convert/toboolean/
---
## Convert::ToBoolean(bool) 方法


傳回指定的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) 方法


將指定的 8 位元無號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) 方法


將指定的 8 位元有號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) 方法


將指定的 16 位元無號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) 方法


將指定的 16 位元有號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) 方法


將指定的 32 位元無號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) 方法


將指定的 32 位元有號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) 方法


將指定的 64 位元無號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) 方法


將指定的 64 位元有號整數轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) 方法


將指定的 float 數字轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) 方法


將指定的 double 數字轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) 方法


將指定的 decimal 數字轉換為等效的布林值。

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) 方法


不支援此轉換。總是拋出 InvalidCastException。

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) 方法


不支援此轉換。總是拋出 InvalidCastException。

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) 方法


將指定的 null 字串轉換為等效的布林值。

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### 返回值

False.

## Convert::ToBoolean(const char_t *) 方法


將指定的 c 字串轉換為 bool 類型的值。

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要轉換的 c 字串 |

### 返回值

如果指定的 c 字串等於 "True" 則傳回 True，否則如果等於 "False" 則傳回 false。

## Convert::ToBoolean(const String\&) 方法


將指定的字串轉換為 bool 類型的值。

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

如果指定的字串等於 "True" 則傳回 True，否則如果等於 "False" 則傳回 false。

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的字串轉換為 bool 類型的值。

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 返回值

如果指定的字串等於 "True" 則傳回 True，否則如果等於 "False" 則傳回 false。

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法


將指定的封裝值轉換為等效的布林值。

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向封裝要轉換之值的物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果封裝值的類型是 [String](../../string/)，則使用的字串格式 |

### 返回值

等同於指定封裝值的布林值

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)