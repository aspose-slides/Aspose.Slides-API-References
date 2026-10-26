---
title: MakeObject()
second_title: Aspose.Slides C++ API 参考
description: 在堆上创建对象并返回指向它的共享指针。
type: docs
weight: 2848
url: /zh/system/makeobject/
---
## System::MakeObject(Args\&&...) 函数


在堆上创建对象并返回指向它的共享指针。

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 要实例化的类。 |
| Args | 构造函数参数的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | 构造函数参数。 |

### 返回值

[SmartPtr](../smartptr/) 指向新创建的对象，始终以共享模式。

## System::MakeObject(Args\&&...) 函数


在堆上创建对象并返回指向它的共享指针。

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [SmartPtr](../smartptr/) 要实例化的类。 |
| Args | 构造函数参数的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| args | Args\&&... | 构造函数参数。 |

### 返回值

[SmartPtr](../smartptr/) 指向新创建的对象，始终以共享模式。

## 另请参见

* 类 [SmartPtr](../smartptr/)
* 结构体 [IsSmartPtr](../issmartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)