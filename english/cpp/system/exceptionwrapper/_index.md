---
title: ExceptionWrapper
second_title: Aspose.Slides for C++ API Reference
description: Template that represents wrapper of exceptions that are derived from Exception class.
type: docs
weight: 794
url: /cpp/system/exceptionwrapper/
---
## ExceptionWrapper class


Template that represents wrapper of exceptions that are derived from Exception class.

```cpp
template<typename T>class ExceptionWrapper
```

## Methods

| Method | Description |
| --- | --- |
|  [ExceptionWrapper](./exceptionwrapper/)(std::nullptr_t) | Constructs a null-instance of [ExceptionWrapper](./) class that does not represent any exception. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionPtr](../exceptionptr/)\&) | Constructs a instance of [ExceptionWrapper](./) class that contains passed pointer. |
|  [ExceptionWrapper](./exceptionwrapper/)(const [ExceptionWrapper](./)\&) | Copy constructor. |
|  [ExceptionWrapper](./exceptionwrapper/)([ExceptionWrapper](./)\&&) | Move constructor. |
| explicit  [ExceptionWrapper](./exceptionwrapper/)(Args\&&...) | Constructor that forwards parameters to the Exception class constructors and creates smart pointer that holds new Exception class instance. |
| static void * [operator new](./operator_new/)(std::size_t) |  |
| static void * [operator new[]](./operator_new[]/)(std::size_t) |  |
|  [operator SharedPtr< Object >](./operator_sharedptr_less_object__greater/)() | Implicit cast operator to SharedPtr<Object> |
| T * [operator->](./operator_minus_greater/)() const | Allows to access members of the Exception object. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)(const [ExceptionWrapper](./)\&) | Assignment operator. |
| [ExceptionWrapper](./)\& [operator=](./operator_equal/)([ExceptionWrapper](./)\&&) | Move assignment operator. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Shortcut to get [System::TypeInfo](../typeinfo/) object for the Exception type. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ExceptionType](./exceptiontype/) | Used for casting functions. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
