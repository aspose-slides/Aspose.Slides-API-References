---
title: ToString()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает строковое значение XmlQualifiedName.
type: docs
weight: 79
url: /ru/system.xml/xmlqualifiedname/tostring/
---
## XmlQualifiedName::ToString() const метод


Возвращает строковое значение [XmlQualifiedName](../).

```cpp
String System::Xml::XmlQualifiedName::ToString() const override
```


### Возвращаемое значение

Строковое значение [XmlQualifiedName](../) в формате **namespace:localname**. Если у объекта не определено пространство имён, этот метод возвращает только локальное имя.

## XmlQualifiedName::ToString(const String\&, const String\&) метод


Возвращает строковое значение [XmlQualifiedName](../).

```cpp
static String System::Xml::XmlQualifiedName::ToString(const String &name, const String &ns)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Имя объекта. |
| ns | const [String](../../../system/string/)\& | Пространство имён объекта. |

### Возвращаемое значение

Строковое значение [XmlQualifiedName](../) в формате **namespace:localname**. Если у объекта не определено пространство имён, этот метод возвращает только локальное имя.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlQualifiedName](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)