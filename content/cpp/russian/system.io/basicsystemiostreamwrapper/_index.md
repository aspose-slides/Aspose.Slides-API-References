---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides для C++ API Reference
description: "Представляет собой обертку, похожую на std::iostream, использующую BasicSystemIOStreamBuf в качестве внутреннего буфера."
type: docs
weight: 53
url: /ru/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper класс

Представляет собой обертку, похожую на std::iostream, использующую [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Используется в конструкторе перемещения и операторе присваивания перемещения для сброса указателей и вызова [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Создаёт новый экземпляр [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Конструктор копирования. Удалён. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Конструктор перемещения. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Оператор присваивания копирования. Удалён. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Оператор присваивания перемещения. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Вызов swap *this и **right**, если они не равны. |

## Типedefы

| Типedef | Описание |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## См. также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)