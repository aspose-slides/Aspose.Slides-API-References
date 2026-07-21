---
title: Version
second_title: Aspose.Slides для C++ справочник API
description: "Представляет номер версии. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1444
url: /ru/system/version/
---
## Version класс

Представляет номер версии. Этот тип должен быть размещён в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Version
```

## Методы

| Метод | Описание |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Сравнивает версии, представленные текущим объектом и указанным объектом. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Определяет, равны ли номера версий, представленные текущим и указанным объектами. |
| int [get_Build](./get_build/)() const | Возвращает номер сборки. |
| int [get_Major](./get_major/)() const | Возвращает основную версию. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Возвращает старшее 16-битное значение номера ревизии. |
| int [get_Minor](./get_minor/)() const | Возвращает младшую версию. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Возвращает младшее 16-битное значение номера ревизии. |
| int [get_Revision](./get_revision/)() const | Возвращает номер ревизии. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код для текущего объекта. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует строковое представление номера версии в эквивалентный экземпляр класса [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Возвращает строковое представление номера версии, представленного текущим объектом. |
| [String](../string/) [ToString](./tostring/)(int) const | Возвращает строковое представление указанного количества секций номера версии, представленного текущим объектом. |
|  [Version](./version/)(int, int, int, int) | Создаёт экземпляр, представляющий указанные значения major, minor, build и revsion. |
|  [Version](./version/)(int, int, int) | Создаёт экземпляр, представляющий указанные значения major, minor и build. |
|  [Version](./version/)(int, int) | Создаёт экземпляр, представляющий указанные значения major и values. |
|  [Version](./version/)(const [String](../string/)\&) | Создаёт экземпляр, представляющий номер версии, заданный в виде строки. |
|  [Version](./version/)() | Создаёт экземпляр, представляющий номер версии 0.0.-1.-1. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)