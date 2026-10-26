---
title: ExceptionWrapper()
second_title: Odwołanie do API Aspose.Slides dla C++
description: Tworzy pustą instancję klasy ExceptionWrapper, która nie reprezentuje żadnego wyjątku.
type: docs
weight: 14
url: /pl/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) konstruktor


Tworzy pustą instancję klasy [ExceptionWrapper](../), która nie reprezentuje żadnego wyjątku.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) konstruktor


Tworzy instancję klasy [ExceptionWrapper](../), która zawiera przekazany wskaźnik.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Inteligentny wskaźnik do instancji klasy Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) konstruktor


Konstruktor kopiujący.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Inna instancja klasy opakowującej, która musi być skopiowana. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) konstruktor


Konstruktor przenoszący.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Inna instancja klasy opakowującej, która musi być przeniesiona. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) konstruktor


Konstruktor, który przekazuje parametry do konstruktorów klasy Exception i tworzy inteligentny wskaźnik, który przechowuje nową instancję klasy Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Zobacz także

* Definicja typu [ExceptionPtr](../../exceptionptr/)
* Klasa [ExceptionWrapper](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)