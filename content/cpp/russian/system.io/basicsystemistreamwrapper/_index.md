---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides для справочника API C++
description: "Представляет собой обёртку, похожую на std::istream, использующую BasicSystemIOStreamBuf в качестве внутреннего буфера."
type: docs
weight: 66
url: /ru/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper класс

Представляет обёртку, похожую на std::istream, использующую [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) в качестве внутреннего буфера.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Используется в конструкторе перемещения и операторе присваивания перемещения для сброса указателей и вызова [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Создаёт новый экземпляр [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Конструктор копирования. Удалён. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Конструктор перемещения. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Оператор присваивания копирования. Удалён. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Оператор присваивания перемещения. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Вызов swap *this и **right**, если они не равны. |

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