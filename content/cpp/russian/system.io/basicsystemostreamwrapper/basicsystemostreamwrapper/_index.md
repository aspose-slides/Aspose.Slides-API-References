---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый экземпляр BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /ru/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) конструктор

Создаёт новый экземпляр [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Указатель на поток |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Режим обертывания |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) конструктор

Конструктор копирования. Удалено.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) конструктор

Конструктор перемещения.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) для перемещения |

## См. также

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../stream/)
* Класс [BasicSystemOStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)