---
title: operator>>()
second_title: Aspose.Slides для C++ справочник API
description: Получает строку из входного потока, используя кодировку UTF-8.
type: docs
weight: 2965
url: /ru/system/operator_greater_greater/
---
## System::operator>>(std::istream\&, String\&) функция


Получает строку из входного потока, используя кодировку UTF-8.

```cpp
std::istream & System::operator>>(std::istream &in, String &str)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in | std::istream\& | Объект входного потока (инстанцирование **basic_ostream** с **char**). |
| str | [String](../string/)\& | Строка для чтения из входного потока. |

### Возвращаемое значение

Входной поток, из которого была извлечена строка.

## System::operator>>(std::wistream\&, String\&) функция


Получает строку из входного потока.

```cpp
std::wistream & System::operator>>(std::wistream &in, String &str)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| in | std::wistream\& | Объект входного потока (инстанцирование **basic_ostream** с ****wchar_t****). |
| str | [String](../string/)\& | Строка для чтения из входного потока. |

### Возвращаемое значение

Входной поток, из которого была извлечена строка.

## См. также

* Класс [String](../string/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)