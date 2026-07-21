---
title: Guid
second_title: Справочник API Aspose.Slides для C++
description: "Представляет глобально уникальный идентификатор. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 885
url: /ru/system/guid/
---
## Guid класс

Represents a Globally Unique IDentifier This type should be allocated on stack and passed to functions by value or by reference. Never use [System::SmartPtr](../smartptr/) class to manage objects of this type.

```cpp
class Guid
```

## Методы

| Метод | Описание |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Выполняет арифметическое сравнение GUIDов, представленных текущим и указанным объектами. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Определяет, равны ли GUIDы, представленные текущим и указанным объектами. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код текущего объекта. |
|  [Guid](./guid/)() | Создаёт объект, представляющий GUID, состоящий из нулей. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Создаёт объект, представляющий GUID, заданный массивом беззнаковых 8-битных целых значений. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Создаёт объект, представляющий GUID, заданный представлением массива беззнаковых 8-битных целых значений. |
|  [Guid](./guid/)(const [String](../string/)\&) | Создаёт объект, представляющий GUID, указанный в виде строки. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Создаёт экземпляр класса [Guid](./) из указанных компонентов GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Создаёт экземпляр класса [Guid](./) из указанных компонентов GUID. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Создаёт экземпляр класса [Guid](./) из указанных беззнаковых целых и байтов. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Создаёт экземпляр класса [Guid](./) из указанных беззнаковых целых и байтов. |
|  [Guid](./guid/)(const [Guid](./)\&) | Создаёт объект, представляющий тот же GUID, что и указанный объект. |
| static [Guid](./) [NewGuid](./newguid/)() | Генерирует новый GUID и возвращает объект [Guid](./), представляющий его. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Определяет, не равны ли GUIDы, представленные текущим и указанным объектами. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Присваивает текущему объекту значение GUID, представленного указанным объектом [Guid](./). |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Определяет, равны ли GUIDы, представленные текущим и указанным объектами. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанное строковое представление GUID в эквивалентный объект [Guid](./). |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Преобразует GUID, представленный текущим объектом, в массив байтов. |
| [String](../string/) [ToString](./tostring/)() const | Преобразует GUID, представленный текущим объектом, в его строковое представление. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Преобразует GUID, представленный текущим объектом, в его строковое представление, используя указанный строковой формат. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Преобразует GUID, представленный текущим объектом, в его строковое представление, используя указанный строковой формат и культуру. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Пытается преобразовать указанную строку в объект [Guid](./). |
|  [~Guid](./~guid/)() | Деструктор. |

## Поля

| Поле | Описание |
| --- | --- |
| static [Empty](./empty/) | Представляет GUID со значением 0. |

## См. также

* Программное пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)