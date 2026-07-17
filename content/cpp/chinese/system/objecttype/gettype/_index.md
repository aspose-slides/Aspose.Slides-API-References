---
title: GetType()
second_title: Aspose.Slides for C++ API 参考
description: 实现 typeof() 翻译。针对智能指针的重载。
type: docs
weight: 1
url: /zh/system/objecttype/gettype/
---
## ObjectType::GetType(const T\&) 方法

实现 typeof() 的翻译。针对智能指针的重载。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 指针对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述所传对象的最终类。

## ObjectType::GetType(const T\&) 方法

实现 typeof() 的翻译。针对结构体的重载。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 结构体类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述所传对象的最终类。

## ObjectType::GetType(const T\&) 方法

实现 typeof() 的翻译。针对异常的重载。

```cpp
template<typename T> static std::enable_if<IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 异常类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to get [TypeInfo](../../typeinfo/) for. |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述所传对象的最终类。

## ObjectType::GetType(const T) 方法

实现 typeof() 的翻译。针对基本类型的重载。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value||std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T | IGNORED |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述所传对象的类型。

## ObjectType::GetType(const T) 方法

实现 typeof() 的翻译。针对 [Nullable](../../nullable/) 类型的重载。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType(const T obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Nullable](../../nullable/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T | IGNORED |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述所传对象的类型。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对基本类型的重载。

```cpp
template<typename T> static std::enable_if<std::is_fundamental<T>::value &&!std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的类型。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对枚举类型的重载。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的类型。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对结构体和指针的重载。

```cpp
template<typename T> static std::enable_if<(!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&!IsBoxable<T>::value)||IsExceptionWrapper<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的结构。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 [Nullable](../../nullable/)。

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Nullable](../../nullable/) 类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的结构。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 MutlicastDelegate。

```cpp
template<typename T> static std::enable_if<detail::is_a<T, MulticastDelegate>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | MutlicastDelegate 类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的结构。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对结构体和指针的重载。

```cpp
template<typename T> static std::enable_if<!std::is_fundamental<T>::value &&!std::is_enum<T>::value &&IsBoxable<T>::value &&!detail::is_a<T, MulticastDelegate>::value &&!IsNullable<T>::value, constSystem::TypeInfo &>::type System::ObjectType::GetType()
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述指定的结构，或者在调用[SmartPtr](../../smartptr/)时返回指向的类型。

## ObjectType::GetType(const String\&) 方法

实现 typeof() 的翻译。针对字符串类型的重载。

```cpp
static const System::TypeInfo & System::ObjectType::GetType(const String &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 基本类型。 |

### 返回值

对[TypeInfo](../../typeinfo/)结构体的常量引用，描述[String](../../string/)类型。

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 **uint8_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 char16_t。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 **int32_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 **int64_t**。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 bool。

```cpp
const System::TypeInfo & System::ObjectInfo::GetType()
```

## ObjectType::GetType() 方法

实现 typeof() 的翻译。针对 [Void](../../void/)。

```cpp
const System::TypeInfo & System::ObjectType::GetType()
```

## 另请参阅

* 类 [ObjectType](../)
* 类 [TypeInfo](../../typeinfo/)
* 类 [String](../../string/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 结构体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 结构体 [IsNullable](../../isnullable/)
* 结构体 [IsBoxable](../../isboxable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)