---
title: BasicSystemIOStreamBuf
second_title: "Aspose.Slides для C++ справочник API"
description: "Представляет буфер, который оборачивает потоки, похожие на System::IO::Stream, и позволяет использовать их в качестве внутреннего буфера потоков, похожих на std::iostream."
type: docs
weight: 40
url: /ru/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf класс

Представляет буфер, который оборачивает потоки, похожие на [System::IO::Stream](../stream/), и позволяет использовать их в качестве внутреннего буфера потоков, похожих на std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Методы

| Метод | Описание |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Используется в конструкторе перемещения и операторе перемещения для сброса указателей и вызова [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Создаёт новый экземпляр [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Создаёт новый экземпляр [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Конструктор копирования. Удалён. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Конструктор перемещения. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Оператор копирующего присваивания. Удалён. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Оператор перемещения присваивания. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Вызов swap *this и right, если они не равны. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Деструктор. |

## Типы

| Тип | Описание |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Смотрите также

* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)