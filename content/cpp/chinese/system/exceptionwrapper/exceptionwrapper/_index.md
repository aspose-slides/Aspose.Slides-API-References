---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个不代表任何异常的 ExceptionWrapper 类的空实例。
type: docs
weight: 14
url: /zh/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) 构造函数

构造一个不代表任何异常的 [ExceptionWrapper](../) 类的空实例。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(stdnullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) 构造函数

构造一个包含所传指针的 [ExceptionWrapper](../) 类实例。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | 指向 Exception 类实例的智能指针。 |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) 构造函数

拷贝构造函数。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | 需要复制的包装器类的另一个实例。 |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) 构造函数

移动构造函数。

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | 需要移动的包装器类的另一个实例。 |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) 构造函数

构造函数将参数转发给 Exception 类的构造函数，并创建一个持有新 Exception 类实例的智能指针。

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## 另请参见

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)