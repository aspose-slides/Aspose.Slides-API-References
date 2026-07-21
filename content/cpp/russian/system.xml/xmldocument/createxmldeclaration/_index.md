---
title: CreateXmlDeclaration()
second_title: Aspose.Slides для C++ справочника API
description: Создает узел XmlDeclaration с указанными значениями.
type: docs
weight: 378
url: /ru/system.xml/xmldocument/createxmldeclaration/
---
## XmlDocument::CreateXmlDeclaration(const String&, const String&, const String&) метод


Создает [XmlDeclaration](../../xmldeclaration/) узел с указанными значениями.

```cpp
virtual SharedPtr<XmlDeclaration> System::Xml::XmlDocument::CreateXmlDeclaration(const String &version, const String &encoding, const String &standalone)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| version | const [String](../../../system/string/)\& | Версия должна быть "1.0". |
| encoding | const [String](../../../system/string/)\& | Значение атрибута encoding. Это кодировка, используемая при сохранении [XmlDocument](../) в файл или поток; поэтому её необходимо установить в строку, поддерживаемую классом [Text::Encoding](../../../system.text/encoding/), иначе вызов "XmlDocument::Save(String)" завершится неудачей. Если значение равно **nullptr** или [String::Empty](../../../system/string/empty/), метод [XmlDocument::Save](../save/) не записывает атрибут encoding в объявление XML и поэтому используется кодировка по умолчанию UTF-8. |
| standalone | const [String](../../../system/string/)\& | Значение должно быть либо "yes", либо "no". Если значение равно **nullptr** или [String::Empty](../../../system/string/empty/), метод [XmlDocument::Save](../save/) не записывает атрибут standalone в объявление XML. |

### Возвращаемое значение

Новый [XmlDeclaration](../../xmldeclaration/) узел.

## Примечания



Примечание: Если [XmlDocument](../) сохраняется в TextWriter или [XmlTextWriter](../../xmltextwriter/), значение этой кодировки отбрасывается. Вместо этого используется кодировка TextWriter или [XmlTextWriter](../../xmltextwriter/). Это гарантирует, что записанный XML можно будет прочитать с правильной кодировкой. 

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlDeclaration](../../xmldeclaration/)
* Класс [String](../../../system/string/)
* Класс [XmlDocument](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)