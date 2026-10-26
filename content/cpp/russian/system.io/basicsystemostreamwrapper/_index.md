---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides для C++: справочник API
description: "Представляет обёртку, похожую на std::ostream, использующую BasicSystemIOStreamBuf в качестве внутреннего буфера."
type: docs
weight: 79
url: /ru/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper класс

Представляет обёртку, похожую на std::ostream, использующую [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Используется в конструкторе перемещения и операторе перемещающего присваивания для сброса указателей и вызова [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Создаёт новый экземпляр [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Конструктор копирования. Удалён. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Конструктор перемещения. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Оператор копирующего присваивания. Удалён. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Оператор перемещающего присваивания. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Вызов swap для *this и **right**, если они не равны. |

## Типы

| Тип | Описание |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)