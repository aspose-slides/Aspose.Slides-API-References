---
title: GetHashCode()
second_title: Aspose.Slides C++ API 参考
description: 返回指定标量值的哈希码。
type: docs
weight: 2445
url: /zh/system/gethashcode/
---
## System::GetHashCode(const T\&) 函数

返回指定标量值的哈希码。

```cpp
template<typename T> std::enable_if<std::is_scalar<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 函数为其生成哈希码的值的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 用于生成哈希码的值 |

### 返回值

为指定值生成的哈希码

## System::GetHashCode(const T\&) 函数

返回指定对象的哈希码。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&System::IsSmartPtr<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 函数为其生成哈希码的对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 指向用于生成哈希码的对象的 [SmartPtr](../smartptr/) |

### 返回值

为指定对象生成的哈希码

## System::GetHashCode(const T\&) 函数

返回指定异常对象的哈希码。

```cpp
template<typename T> std::enable_if<System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 函数为其生成哈希码的对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 包含用于生成哈希码的对象的 Exception Wrapper |

### 返回值

为指定对象生成的哈希码

## System::GetHashCode(const T\&) 函数

返回指定对象（既不是智能指针也不是异常）的哈希码。

```cpp
template<typename T> std::enable_if<!std::is_scalar<T>::value &&!System::IsSmartPtr<T>::value &&!System::IsExceptionWrapper<T>::value, int>::type System::GetHashCode(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 函数为其生成哈希码的对象的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 用于生成哈希码的对象的 const 引用 |

### 返回值

为指定对象生成的哈希码

## System::GetHashCode(const std::thread::id\&) 函数

针对 std::thread::id 的特化；返回指定线程对象的哈希码。

```cpp
int System::GetHashCode(const std::thread::id &id)
```

## 另见

* 结构体 [IsSmartPtr](../issmartptr/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)