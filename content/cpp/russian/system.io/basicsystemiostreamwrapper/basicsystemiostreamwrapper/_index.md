---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides для C++: справочник API
description: Создаёт новый экземпляр BasicSystemIOStreamWrapper.
type: docs
weight: 1
url: /ru/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor


Создаёт новый экземпляр [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Указатель на поток |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Режим обёртывания |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) constructor


Конструктор копирования. Удалён.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) constructor


Конструктор перемещения.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) для перемещения |

## See Also

* Перечисление [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Stream](../../stream/)
* Класс [BasicSystemIOStreamWrapper](../)
* Пространство имён [System::IO](../../)
* Библиотека [Aspose.Slides](../../../)