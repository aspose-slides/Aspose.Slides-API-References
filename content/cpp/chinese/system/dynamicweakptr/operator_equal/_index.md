---
title: operator=()
second_title: Aspose.Slides for C++ API 参考
description: 移动赋值智能指针。
type: docs
weight: 27
url: /zh/system/dynamicweakptr/operator_equal/
---
## DynamicWeakPtr::operator=(SmartPtr_&&) 方法

移动赋值智能指针。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(SmartPtr_ &&x)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)&& | 要进行移动赋值的指针。 |

### 返回值

自身引用。

## DynamicWeakPtr::operator=(const SmartPtr_&) 方法

复制赋值智能指针。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr_ &x)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr_](../smartptr_/)& | 要进行复制赋值的指针。 |

### 返回值

自身引用。

## DynamicWeakPtr::operator=(const SmartPtr<Q>&) 方法

复制赋值智能指针。

```cpp
template<typename Q> DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(const SmartPtr<Q> &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 源指向对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)<Q>& | 要进行复制赋值的指针。 |

### 返回值

自身引用。

## DynamicWeakPtr::operator=(typename SmartPtr_::Pointee_ *) 方法

赋值智能指针。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(typename SmartPtr_::Pointee_ *p)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p | typename [SmartPtr_::Pointee_](../../smartptr/pointee_/) * | 指针值。 |

### 返回值

自身引用。

## DynamicWeakPtr::operator=(std::nullptr_t) 方法

将智能指针设为null。

```cpp
DynamicWeakPtr_ & System::DynamicWeakPtr<T, trunkMode, weakLeafs>::operator=(std::nullptr_t)
```

### 返回值

自身引用。

## 另请参见

* 类型别名 [DynamicWeakPtr_](../dynamicweakptr_/)
* 类型别名 [SmartPtr_](../smartptr_/)
* 类型别名 [Pointee_](../../smartptr/pointee_/)
* 类 [DynamicWeakPtr](../)
* 类 [SmartPtr](../../smartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)