---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API 参考
description: 将原始指针转换为智能指针。
type: docs
weight: 2861
url: /zh/system/makesharedptr/
---
## System::MakeSharedPtr(X *) 函数


将原始指针转换为智能指针。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 被指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | X * | 指向对象的原始指针。 |

### 返回值

指向对象的共享智能指针。

## System::MakeSharedPtr(const X *) 函数


将原始指针转换为智能指针。针对 const 指针的重载。适用于在 C# 方法中使用被翻译为 const 的 'this' 变量等情况。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| X | 被指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | const X * | 指向对象的原始指针。 |

### 返回值

指向对象的共享智能指针。

## 参见

* 类 [SmartPtr](../smartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)