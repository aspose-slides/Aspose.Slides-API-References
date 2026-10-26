---
title: get_Name()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает квалифицированное имя текущего узла.
type: docs
weight: 14
url: /ru/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() метод

Возвращает квалифицированное имя текущего узла.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Возвращаемое значение

Квалифицированное имя текущего узла. Например, **Name** равно **bk:book** для элемента **<bk:book>**.

## Примечания

Возвращаемое имя зависит от XmlValidatingReader::NodeType узла. Следующие типы узлов возвращают указанные значения. Все остальные типы узлов возвращают пустую строку. 

| Тип узла | Имя |
| --- | --- |
| [Attribute](../../../system/attribute/)| Имя атрибута. |
| DocumentType| Имя типа документа. |
| Element| Имя тега. |
| EntityReference| Имя ссылки на сущность. |
| ProcessingInstruction| Цель инструкции обработки. |
| [XmlDeclaration](../../xmldeclaration/)| Буквальная строка `xml`. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlValidatingReader](../)
* Пространство имен [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)