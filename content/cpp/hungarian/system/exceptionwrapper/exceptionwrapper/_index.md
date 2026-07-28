---
title: ExceptionWrapper()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy null-példányt az ExceptionWrapper osztályból, amely nem képvisel semmilyen kivételt.
type: docs
weight: 14
url: /hu/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) konstruktor


Készít egy null-példányt a [ExceptionWrapper](../) osztályból, amely nem képvisel semmilyen kivételt.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) konstruktor


Készít egy példányt a [ExceptionWrapper](../) osztályból, amely tartalmazza a átadott mutatót.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Intelligens mutató az Exception osztály példányára. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) konstruktor


Másoló konstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Másik példány a wrapper osztályból, amelyet másolni kell. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) konstruktor


Mozgató konstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Másik példány a wrapper osztályból, amelyet át kell mozgatni. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) konstruktor


Olyan konstruktor, amely továbbítja a paramétereket az Exception osztály konstruktoraira, és intelligens mutatót hoz létre, amely az új Exception osztálypéldányt tartalmazza.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Lásd még

* Typedef [ExceptionPtr](../../exceptionptr/)
* Class [ExceptionWrapper](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)