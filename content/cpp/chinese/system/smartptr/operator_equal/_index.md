---
title: operator=()
second_title: Aspose.Slides for C++ API 参考
description: 移动分配 SmartPtr 对象。x 将不可用。
type: docs
weight: 27
url: /zh/system/smartptr/operator_equal/
---
## SmartPtr::operator=(SmartPtr_&&) 方法

移动分配 [SmartPtr](../) 对象。x 将不可用。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(SmartPtr_ &&x) noexcept
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 指向要移动分配的指针。 |

### 返回值

对该对象的引用。

## SmartPtr::operator=(const SmartPtr_&) 方法

复制赋值 [SmartPtr](../) 对象。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr_ &x)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)\& | 指向要复制赋值的指针。 |

### 返回值

对该对象的引用。

## SmartPtr::operator=(const SmartPtr<Q>&) 方法

复制赋值 [SmartPtr](../) 对象。执行所需的类型转换。

```cpp
template<typename Q> SmartPtr_ & System::SmartPtr<T>::operator=(const SmartPtr<Q> &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | x 所指向的对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../)<Q>\& | 指向要复制赋值的指针。 |

### 返回值

对该对象的引用。

## SmartPtr::operator=(Pointee_ *) 方法

将原始指针分配给 [SmartPtr](../) 对象。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(Pointee_ *p)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | [Pointee_](../pointee_/) * | 要分配的指针值。 |

### 返回值

对该对象的引用。

## SmartPtr::operator=(std::nullptr_t) 方法

将指针值设为 nullptr。

```cpp
SmartPtr_ & System::SmartPtr<T>::operator=(std::nullptr_t)
```

### 返回值

对该对象的引用。

## 另见

* 类型别名 [SmartPtr_](../smartptr_/)
* 类型别名 [Pointee_](../pointee_/)
* 类 [SmartPtr](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)