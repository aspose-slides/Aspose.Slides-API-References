---
title: HasFeature()
second_title: Справка по API Aspose.Slides для C++
description: Проверяет, реализует ли реализация Document Object Model (DOM) конкретную функцию.
type: docs
weight: 14
url: /ru/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) метод


Проверяет, реализует ли реализация модели Document [Object](../../../system/object/) (DOM) конкретную функцию.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Имя пакета функции для проверки. Это имя не чувствительно к регистру. |
| strVersion | const [String](../../../system/string/)\& | Номер версии пакета функции для проверки. Если версия не указана (**nullptr**), поддержка любой версии функции приводит к возврату **true**. |

### Возвращаемое значение

**true**, если функция реализована в указанной версии; в противном случае **false**.

## Примечания



Следующая таблица показывает комбинации, при которых **HasFeature** возвращает **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## См. также

* Класс [String](../../../system/string/)
* Класс [XmlImplementation](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)