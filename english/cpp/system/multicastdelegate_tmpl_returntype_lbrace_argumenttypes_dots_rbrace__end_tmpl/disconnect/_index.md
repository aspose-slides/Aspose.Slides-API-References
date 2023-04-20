---
title: disconnect()
second_title: Aspose.Slides for C++ API Reference
description: Removes the specified delegate from the delegate collection.
type: docs
weight: 157
url: /cpp/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method


Removes the specified delegate from the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | The delegate to remove from the collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method


Removes the specified non-static method of the specified object from the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | ClassType * | A pointer to an object member method of which is to be removed from the delegate collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method


Removes the specified non-static method of the specified object from the delegate collection.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | The type of the non-static method that is to be removed from the delegate collection |
| ClassType | The type of the object method of which is to be removed from the delegate collection |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | A pointer to the non-static method of the specified object |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | A shared pointer to an object member method of which is to be removed from the delegate collection |

### Return Value

A reference to the self

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method


Removes the specified MulticastDelegate object from the delegate collection.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | An instance of the MulticastDelegate class to remove from the delegate collection |

### Return Value

A reference to the self

## See Also

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)