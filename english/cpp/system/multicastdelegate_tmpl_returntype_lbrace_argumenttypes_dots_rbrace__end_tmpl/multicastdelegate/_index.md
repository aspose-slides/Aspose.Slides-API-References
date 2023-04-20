---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an empty collection.
type: docs
weight: 1
url: /cpp/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method


Constructs an empty collection.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method


Equivalent to defalt constructor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method


Performs a shallow copy of the delegate collection.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| o | const MulticastDelegate\& | An instance of MulticastDelegate class to copy the collection of delegates from. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method


Moving constructor.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| o | MulticastDelegate\&& | An instance of MulticastDelegate class to move the collection of delegates from. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method


Constructs an instance and puts the specified delegate to the delegates collection.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | A delegate to put to the delegate collection |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method


Constructs an instance and puts the specified value to the delegates collection.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type of the value to put to the delegate collection of the newly constructed instance; the type must be convertible to Callback type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | A value to put to the delegate collection |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method


Constructs an instance and puts the specified value to the delegates collection.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | A value to put to the delegate collection |

## See Also

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)