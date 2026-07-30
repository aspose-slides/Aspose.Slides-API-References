---
title: ExceptionWrapper()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří nulovou instanci třídy ExceptionWrapper, která nepředstavuje žádnou výjimku.
type: docs
weight: 14
url: /cs/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) konstruktor

Vytvoří nulovou instanci třídy [ExceptionWrapper](../), která nepředstavuje žádnou výjimku.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) konstruktor

Vytvoří instanci třídy [ExceptionWrapper](../), která obsahuje předaný ukazatel.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Chytrý ukazatel na instanci třídy Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) konstruktor

Kopírovací konstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Jiná instance třídy wrapper, která musí být zkopírována. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) konstruktor

Přesunovací konstruktor.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Jiná instance třídy wrapper, která musí být přesunuta. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) konstruktor

Konstruktor, který předává parametry konstruktorům třídy Exception a vytváří chytrý ukazatel, který drží novou instanci třídy Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## Viz také

* Typedef [ExceptionPtr](../../exceptionptr/)
* Třída [ExceptionWrapper](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)