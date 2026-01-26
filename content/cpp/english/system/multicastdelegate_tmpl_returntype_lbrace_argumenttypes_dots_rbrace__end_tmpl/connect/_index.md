---
title: connect()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified delegate to the collection.
type: docs
weight: 144
url: /system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) method


Adds the specified delegate to the collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | The delegate to add to the collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) method


Adds the specified function object to the delegate collection. The function object is converted to the Callback delegate type before being added to the collection.

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| R | The return type of the function object to add to the collection |
| Args | The argument list of the function object to add to the collection |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| f | std::function\<R(Args...)> | The function object to add to the collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) method


Adds the specified MulticastDelegate object to the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | An instance of the MulticastDelegate class to add to the delegate collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) method


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be added to the delegate collection |
| ClassType | The type of the object method of which is to be added to the delegate |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | ClassType * | A pointer to an object member method of which is to be added to the delegate collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Adds the specified non-static method of the specified object to the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be added to the delegate collection |
| ClassType | The type of the object method of which is to be added to the delegate collection |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | A shared pointer to an object member method of which is to be added to the delegate collection |

### Return Value

A reference to the self

## See Also

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)