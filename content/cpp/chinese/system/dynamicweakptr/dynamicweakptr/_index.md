---
title: DynamicWeakPtr()
second_title: Aspose.Slides C++ API 参考
description: 创建空智能指针。
type: docs
weight: 1
url: /zh/system/dynamicweakptr/dynamicweakptr/
---
## DynamicWeakPtr::DynamicWeakPtr(std::nullptr_t) 构造函数

创建空智能指针。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(std::nullptr_t=nullptr)
```

## DynamicWeakPtr::DynamicWeakPtr(Pointee_ *) 构造函数

创建指向给定对象的智能指针。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(Pointee_ *object)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | 被指对象。 |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr_\&) 构造函数

复制构造智能指针。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr_ &ptr)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 用于复制被指对象信息的智能指针。 |

## DynamicWeakPtr::DynamicWeakPtr(const SmartPtr\<Q\>\&) 构造函数

复制构造智能指针。

```cpp
template<class Q> System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const SmartPtr<Q> &x)
```

### 模板参数

| Parameter | Description |
| --- | --- |
| Q | 源指针被指对象类型。 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 用于复制被指对象信息的智能指针。 |

## DynamicWeakPtr::DynamicWeakPtr(const DynamicWeakPtr_\&) 构造函数

复制构造智能指针。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(const DynamicWeakPtr_ &ptr)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [DynamicWeakPtr_](../dynamicweakptr_/)\& | 用于复制被指对象信息的智能指针。 |

## DynamicWeakPtr::DynamicWeakPtr(SmartPtr_\&&) 构造函数

移动构造智能指针。

```cpp
System::DynamicWeakPtr<T, trunkMode, weakLeafs>::DynamicWeakPtr(SmartPtr_ &&x)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 用于移动被指对象信息的智能指针。调用后将不可用。 |

## 另请参见

* 类型定义 [Pointee_](../../smartptr/pointee_/)
* 类型定义 [SmartPtr_](../smartptr_/)
* 类型定义 [DynamicWeakPtr_](../dynamicweakptr_/)
* 类 [DynamicWeakPtr](../)
* 类 [SmartPtr](../../smartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)