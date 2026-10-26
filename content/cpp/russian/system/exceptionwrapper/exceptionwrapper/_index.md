---
title: ExceptionWrapper()
second_title: Справочник API Aspose.Slides для C++
description: Создает нулевой экземпляр класса ExceptionWrapper, который не представляет ни одного исключения.
type: docs
weight: 14
url: /ru/system/exceptionwrapper/exceptionwrapper/
---
## ExceptionWrapper::ExceptionWrapper(std::nullptr_t) конструктор

Создает нулевой экземпляр класса [ExceptionWrapper](../), который не представляет ни одного исключения.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(std::nullptr_t)
```

## ExceptionWrapper::ExceptionWrapper(const ExceptionPtr\&) конструктор

Создает экземпляр класса [ExceptionWrapper](../), содержащий переданный указатель.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionPtr &ptr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | const [ExceptionPtr](../../exceptionptr/)\& | Умный указатель на экземпляр класса Exception. |

## ExceptionWrapper::ExceptionWrapper(const ExceptionWrapper\&) конструктор

Конструктор копирования.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(const ExceptionWrapper &other)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [ExceptionWrapper](../)\& | Другой экземпляр класса-обертки, который необходимо скопировать. |

## ExceptionWrapper::ExceptionWrapper(ExceptionWrapper\&&) конструктор

Конструктор перемещения.

```cpp
System::ExceptionWrapper<T>::ExceptionWrapper(ExceptionWrapper &&other) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | [ExceptionWrapper](../)\&& | Другой экземпляр класса-обертки, который необходимо переместить. |

## ExceptionWrapper::ExceptionWrapper(Args\&&...) конструктор

Конструктор, который передает параметры конструкторам класса Exception и создает умный указатель, содержащий новый экземпляр класса Exception.

```cpp
template<typename ...,typename> System::ExceptionWrapper<T>::ExceptionWrapper(Args &&...args)
```

## См. также

* Typedef [ExceptionPtr](../../exceptionptr/)
* Класс [ExceptionWrapper](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)