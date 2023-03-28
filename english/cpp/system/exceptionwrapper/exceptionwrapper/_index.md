---
title: ExceptionWrapper()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a null-instance of ExceptionWrapper class that does not represent any exception.
type: docs
weight: 14
url: /cpp/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) constructor


Constructs a null-instance of [ExceptionWrapper](../) class that does not represent any exception.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## See Also

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ExceptionWrapper::ExceptionWrapper(const [ExceptionPtr](../../exceptionptr/)\&) constructor


Constructs a instance of [ExceptionWrapper](../) class that contains passed pointer.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Smart pointer to the instance of Exception class. |

## See Also

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ExceptionWrapper::ExceptionWrapper(const [ExceptionWrapper](../)\&) constructor


Copy constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Other instance of wrapper class that must be copied. |

## See Also

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ExceptionWrapper::ExceptionWrapper([ExceptionWrapper](../)\&&) constructor


Move constructor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Other instance of wrapper class that must be moved. |

## See Also

* Class [ExceptionWrapper](../)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ExceptionWrapper::ExceptionWrapper(Args\&&...) constructor


Constructor that forwards parameters to the Exception class constructors and creates smart pointer that holds new Exception class instance.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## See Also

* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
