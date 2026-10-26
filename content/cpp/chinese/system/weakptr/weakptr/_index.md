---
title: WeakPtr()
second_title: Aspose.Slides for C++ API 参考
description: 创建空指针。
type: docs
weight: 1
url: /zh/system/weakptr/weakptr/
---
## WeakPtr::WeakPtr(std::nullptr_t) 构造函数

创建空指针。

```cpp
System::WeakPtr<T>::WeakPtr(std::nullptr_t=nullptr)
```

## WeakPtr::WeakPtr(Pointee_ *) 构造函数

创建指向给定对象的弱指针。

```cpp
System::WeakPtr<T>::WeakPtr(Pointee_ *object)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | [Pointee_](../../smartptr/pointee_/) * | [Object](../../object/) 用于创建弱指针。 |

## WeakPtr::WeakPtr(const SmartPtr_\&) 构造函数

创建引用与 ptr 指向的相同指针的弱指针。

```cpp
System::WeakPtr<T>::WeakPtr(const SmartPtr_ &ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../../smartptr/smartptr_/)\& | 用于复制被指对象值的指针。 |

## WeakPtr::WeakPtr(const SmartPtr\<Q\>\&) 构造函数

创建引用与 x 指向的相同指针的弱指针。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const SmartPtr<Q> &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 源指针的被指对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../../smartptr/)\<Q\>\& | 用于复制被指对象值的指针。 |

## WeakPtr::WeakPtr(const WeakPtr_\&) 构造函数

拷贝构造弱指针。

```cpp
System::WeakPtr<T>::WeakPtr(const WeakPtr_ &ptr)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [WeakPtr_](../weakptr_/)\& | 用于复制被指对象值的指针。 |

## WeakPtr::WeakPtr(const WeakPtr\<Q\>\&) 构造函数

拷贝构造弱指针。

```cpp
template<class Q,typename> System::WeakPtr<T>::WeakPtr(const WeakPtr<Q> &x)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | 源被指对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [WeakPtr](../)\<Q\>\& | 用于复制被指对象值的指针。 |

## WeakPtr::WeakPtr(SmartPtr_\&&) 构造函数

移动构造弱指针。

```cpp
System::WeakPtr<T>::WeakPtr(SmartPtr_ &&x)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../../smartptr/smartptr_/)\&& | 用于移动被指对象值的指针。 |

## 另请参见

* 类型定义 [Pointee_](../../smartptr/pointee_/)
* 类型定义 [SmartPtr_](../../smartptr/smartptr_/)
* 类型定义 [WeakPtr_](../weakptr_/)
* 类 [WeakPtr](../)
* 类 [SmartPtr](../../smartptr/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)