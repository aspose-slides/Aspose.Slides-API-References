---
title: ExceptionWrapper()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en null-instans av ExceptionWrapper-klass som inte representerar något undantag.
type: docs
weight: 14
url: /sv/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) konstruktor


Skapar en null-instans av [ExceptionWrapper](../) klass som inte representerar något undantag.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) konstruktor


Skapar en instans av [ExceptionWrapper](../) klass som innehåller den överförda pekaren.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Smartpekare till instansen av Exception-klass. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) konstruktor


Kopieringskonstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Annan instans av wrapper-klass som måste kopieras. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) konstruktor


Flyttkonstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Annan instans av wrapper-klass som måste flyttas. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) konstruktor


Konstruktor som vidarebefordrar parametrar till Exception-klassens konstruktorer och skapar en smartpekare som håller en ny Exception-klassinstans.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Se även

* Typedef [ExceptionPtr](../../exceptionptr/)
* Klass [ExceptionWrapper](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)