---
title: GetType()
second_title: Aspose.Slides for C++ API 參考
description: 實作 typeof() 轉換。針對智慧指標的重載。
type: docs
weight: 1
url: /zh-hant/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) 方法

Implements typeof() translation. Overload for 智慧指標。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 指標物件類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 以取得 [TypeInfo](../../typeinfo/)。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述傳入物件的最終類別。

## ObjectType::GetType(const T\&) 方法

Implements typeof() translation. Overload for 結構。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 結構類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 以取得 [TypeInfo](../../typeinfo/)。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述傳入物件的最終類別。

## ObjectType::GetType(const T\&) 方法

Implements typeof() translation. Overload for 例外。

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 例外類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 以取得 [TypeInfo](../../typeinfo/)。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述傳入物件的最終類別。

## ObjectType::GetType(const T) 方法

Implements typeof() translation. Overload for 原始類型。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T | IGNORED |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述傳入物件的類型。

## ObjectType::GetType(const T) 方法

Implements typeof() translation. Overload for [Nullable](../../nullable/) 類型。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Nullable](../../nullable/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T | IGNORED |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述傳入物件的類型。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for 原始類型。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 返回値

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的類型。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for 列舉類型。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的類型。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for 結構與指標。

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的結構。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for [Nullable](../../nullable/)。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Nullable](../../nullable/) 類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的結構。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for MutlicastDelegate。

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | MutlicastDelegate 類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的結構。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for 結構與指標。

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述指定的結構；若為 [SmartPtr](../../smartptr/) 呼叫則返回所指向的類型。

## ObjectType::GetType(const String\&) 方法

Implements typeof() translation. Overload for 字串類型。

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 原始類型。 |

### 返回值

對 [TypeInfo](../../typeinfo/) 結構的常量引用，描述 [String](../../string/) 類型。

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for **uint8_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for char16_t。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for **int32_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for **int64_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for bool。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

Implements typeof() translation. Overload for [Void](../../void/)。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## 參見

* 類別 [ObjectType](../)
* 類別 [TypeInfo](../../typeinfo/)
* 類別 [String](../../string/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 結構 [IsExceptionWrapper](../../isexceptionwrapper/)
* 結構 [IsNullable](../../isnullable/)
* 結構 [IsBoxable](../../isboxable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)