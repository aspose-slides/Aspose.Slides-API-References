---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе возвращает квалифицированное имя текущего узла.
type: docs
weight: 27
url: /ru/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() метод

При переопределении в производном классе возвращает квалифицированное имя текущего узла.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### Возвращаемое значение

Квалифицированное имя текущего узла. Например, **Name** равно **bk:book** для элемента **<bk:book>**.

## Примечания

Возвращаемое имя зависит от значения [XmlReader::get_NodeType](../get_nodetype/) узла. Ниже перечислены типы узлов, которые возвращают указанные значения. Все остальные типы узлов возвращают пустую строку. 

| Тип узла | Имя |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Имя атрибута. |
| `DocumentType`| Имя типа документа. |
| `Element`| Имя тега. |
| `EntityReference`| Имя ссылки на сущность. |
| `ProcessingInstruction`| Цель инструкций обработки. |
| [XmlDeclaration](../../xmldeclaration/)| Буквальная строка `xml`. |

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)