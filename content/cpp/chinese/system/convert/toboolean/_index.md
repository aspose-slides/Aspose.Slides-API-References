---
title: ToBoolean()
second_title: Aspose.Slides C++ API 参考
description: 返回指定的布尔值。
type: docs
weight: 79
url: /zh/system/convert/toboolean/
---
## Convert::ToBoolean(bool) 方法

返回指定的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) 方法

将指定的 8 位无符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) 方法

将指定的 8 位有符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) 方法

将指定的 16 位无符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) 方法

将指定的 16 位有符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) 方法

将指定的 32 位无符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) 方法

将指定的 32 位有符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) 方法

将指定的 64 位无符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) 方法

将指定的 64 位有符号整数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) 方法

将指定的浮点数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) 方法

将指定的双精度数转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) 方法

将指定的十进制数转换为等价的布尔值。

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) 方法

不支持转换。始终抛出 InvalidCastException。

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) 方法

将指定的 null 字符串转换为等价的布尔值。

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```

### 返回值

False。

## Convert::ToBoolean(const char_t *) 方法

将指定的 C 字符串转换为 bool 类型的值。

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const char_t * | 要转换的 C 字符串 |

### 返回值

如果指定的 c-string 等于 "True" 则返回 True，否则如果等于 "False" 则返回 false。

## Convert::ToBoolean(const String\&) 方法

将指定的字符串转换为 bool 类型的值。

```cpp
static bool System::Convert::ToBoolean(const String &value)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

如果指定的 c-string 等于 "True" 则返回 True，否则如果等于 "False" 则返回 false。

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的字符串转换为 bool 类型的值。

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要转换的字符串 |

### 返回值

如果指定的 c-string 等于 "True" 则返回 True，否则如果等于 "False" 则返回 false。

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

将指定的装箱值转换为等价的布尔值。

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 指向装箱值对象的共享指针 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 当装箱值的类型为 [String](../../string/) 时使用的字符串格式 |

### 返回值

等价于指定装箱值的布尔值。

## 另请参阅

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)