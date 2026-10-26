---
title: SmartPtr()
second_title: Aspose.Slides for C++ API 参考
description: 创建所需模式的 SmartPtr 对象。
type: docs
weight: 1
url: /zh/system/smartptr/smartptr/
---
## SmartPtr::SmartPtr(SmartPtrMode) 构造函数


创建所需模式的[SmartPtr](../)对象。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtrMode mode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(std::nullptr_t, SmartPtrMode) 构造函数


创建所需模式的空指针[SmartPtr](../)对象。

```cpp
System::SmartPtr<T>::SmartPtr(std::nullptr_t=nullptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mode | std::nullptr_t | 指针模式。 |

## SmartPtr::SmartPtr(Pointee_ *, SmartPtrMode) 构造函数


创建指向指定对象的[SmartPtr](../)，或将原始指针转换为[SmartPtr](../)。

```cpp
System::SmartPtr<T>::SmartPtr(Pointee_ *object, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| object | [Pointee_](../pointee_/) * | 被指对象。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(const SmartPtr_, SmartPtrMode) 构造函数


复制构造[SmartPtr](../)对象。之后两个指针指向同一对象。

```cpp
System::SmartPtr<T>::SmartPtr(const SmartPtr_ &ptr, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr_](../smartptr_/)\& | 要复制的指针。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(const SmartPtr\<Q\>\&, SmartPtrMode) 构造函数


复制构造[SmartPtr](../)对象。之后两个指针指向同一对象。如果允许，执行类型转换。

```cpp
template<class Q,typename> System::SmartPtr<T>::SmartPtr(const SmartPtr<Q> &x, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Q | x 所指对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | const [SmartPtr](../)\<Q\>\& | 要复制的指针。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(SmartPtr_&&, SmartPtrMode) 构造函数


移动构造[SmartPtr](../)对象。实际上，如果两个指针模式相同，则交换它们。调用后x可能不可用。

```cpp
System::SmartPtr<T>::SmartPtr(SmartPtr_ &&x, SmartPtrMode mode=SmartPtrMode::Shared) noexcept
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | [SmartPtr_](../smartptr_/)\&& | 要移动的指针。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(const SmartPtr\<Array\<Y\>\>\&, SmartPtrMode) 构造函数


通过创建不同类型的新数组来转换引用数组的类型。如果在C#中有数组类型转换但在C++中不支持，此功能很有用。

```cpp
template<typename Y> System::SmartPtr<T>::SmartPtr(const SmartPtr<Array<Y>> &src, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | 源数组的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| src | const [SmartPtr](../)\<[Array](../../array/)\<Y\>\>\& | 要创建副本的数组指针，但元素类型不同。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 |

## SmartPtr::SmartPtr(const Y\&) 构造函数


初始化空数组。用于转换某些C#代码构造。

```cpp
template<typename Y,typename> System::SmartPtr<T>::SmartPtr(const Y &)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| Y | EmptyArrayInitializer 类型的占位符。 |

## SmartPtr::SmartPtr(const SmartPtr\<P\>\&, Pointee_ *, SmartPtrMode) 构造函数


构造一个[SmartPtr](../)，它与ptr的初始值共享所有权信息，但持有一个不相关且未受管理的指针p。

```cpp
template<typename P> System::SmartPtr<T>::SmartPtr(const SmartPtr<P> &ptr, Pointee_ *p, SmartPtrMode mode=SmartPtrMode::Shared)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ptr | const [SmartPtr](../)\<P\>\& | 共享所有权的另一个智能指针。 |
| p | [Pointee_](../pointee_/) * | 要管理的对象指针。 |
| mode | [SmartPtrMode](../../smartptrmode/) | 指针模式。 
```cpp
#include "system/object.h"
#include "system/smart_ptr.h"
#include <iostream>

// 此类包含一个将被打印的字段。
class Foo : public System::Object
{
public:
  std::string value = "Hello, world!";
};

// 此类包含一个 Foo 类的实例。
class Bar : public System::Object
{
public:
  Foo data;
};

// 用于打印 Foo 类实例中的字符串。
void PrintMessage(const System::SharedPtr<Foo> &foo)
{
  std::cout << foo->value << std::endl;
}

// 打印指向该对象的共享指针数量。
void PrintSharedCount(const System::SharedPtr<Bar> &ptr)
{
  std::cout << "Number of shared pointers: " << ptr.get_shared_count() << std::endl;
}

int main()
{
  // 创建指向 Bar 类实例的 SharedPtr。
  auto bar = System::MakeObject<Bar>();
  PrintSharedCount(bar);
  // 创建指向 Bar 类实例字段的 SharedPtr。
  auto foo = System::SharedPtr<Foo>(bar, &bar->data);
  PrintSharedCount(bar);

  // 将 'bar' 指针设为 nullptr。
  bar.reset();
  PrintSharedCount(bar);
  // bar->data 仍然存在，且 'foo' 指针有效。
  PrintMessage(foo);

  return 0;
}
/*
此代码示例产生以下输出:
Number of shared pointers: 1
Number of shared pointers: 2
Number of shared pointers: 0
Hello, world!
*/
``` |

## 另请参阅

* Enum [SmartPtrMode](../../smartptrmode/)
* Typedef [Pointee_](../pointee_/)
* Typedef [SmartPtr_](../smartptr_/)
* Class [SmartPtr](../)
* Class [Array](../../array/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)