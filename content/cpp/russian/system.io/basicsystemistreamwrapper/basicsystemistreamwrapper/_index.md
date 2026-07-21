---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /ru/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) конструктор

Создаёт новый экземпляр [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Указатель на поток |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Режим обёртывания |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) конструктор

Конструктор копирования. Удалён.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) конструктор

Конструктор перемещения.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) для перемещения |

## См. также

* Перечисление [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* класс [Stream](../../stream/)
* класс [BasicSystemIStreamWrapper](../)
* пространство имён [System::IO](../../)
* библиотека [Aspose.Slides](../../../)