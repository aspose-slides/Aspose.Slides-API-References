---
title: connect()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的委托添加到集合中。
type: docs
weight: 144
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) 方法

将指定的委托添加到集合中。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| callback | [Callback](../callback/) | 要添加到集合中的委托 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) 方法

将指定的函数对象添加到委托集合中。在添加到集合之前，函数对象会被转换为 Callback 委托类型。

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| R | 要添加到集合中的函数对象的返回类型 |
| Args | 要添加到集合中的函数对象的参数列表 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | 要添加到集合中的函数对象 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) 方法

将指定的 MulticastDelegate 对象添加到委托集合中。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 要添加到委托集合中的 MulticastDelegate 类的实例 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) 方法

将指定对象的指定非静态方法添加到委托集合中。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| MemberType | 要添加到委托集合中的非静态方法的类型 |
| ClassType | 要添加到委托中的对象方法所属的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定对象的非静态方法指针 |
| obj | ClassType * | 指向要添加到委托集合的对象成员方法的指针 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) 方法

将指定对象的指定非静态方法添加到委托集合中。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| MemberType | 要添加到委托集合中的非静态方法的类型 |
| ClassType | 要添加到委托中的对象方法所属的类型 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定对象的非静态方法指针 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 指向要添加到委托集合的对象成员方法的共享指针 |

### 返回值

对自身的引用

## 另见

* 类型定义 [Callback](../callback/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 方法 [MulticastDelegate](../multicastdelegate/)
* 类 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)