---
title: disconnect()
second_title: Aspose.Slides for C++ API 参考
description: 从委托集合中移除指定的委托。
type: docs
weight: 170
url: /zh/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) 方法


从委托集合中移除指定的委托。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | 要从集合中移除的委托 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) 方法


从委托集合中移除指定对象的指定非静态方法。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| MemberType | 要从委托集合中移除的非静态方法的类型 |
| ClassType | 要从委托集合中移除的对象方法所属的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | 指向指定对象的非静态方法的指针 |
| obj | ClassType * | 指向要从委托集合中移除的对象成员方法的指针 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) 方法


从委托集合中移除指定对象的指定非静态方法。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### 模板参数

| Parameter | Description |
| --- | --- |
| MemberType | 要从委托集合中移除的非静态方法的类型 |
| ClassType | 要从委托集合中移除的对象方法所属的类型 |

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | 指向指定对象的非静态方法的指针 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 指向要从委托集合中移除的对象成员方法的共享指针 |

### 返回值

对自身的引用

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) 方法


从委托集合中移除指定的 MulticastDelegate 对象。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 要从委托集合中移除的 MulticastDelegate 类实例 |

### 返回值

对自身的引用

## 另请参阅

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)