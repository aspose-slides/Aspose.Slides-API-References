---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает квалифицированное имя текущего узла.
type: docs
weight: 14
url: /ru/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() метод


Возвращает квалифицированное имя текущего узла.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Возвращаемое значение

Квалифицированное имя текущего узла. Например, **Name** равно **bk:book** для элемента **<bk:book>**.

## Примечания



Возвращаемое имя зависит от значения [XmlTextReader::get_NodeType](../get_nodetype/) узла. Следующие типы узлов возвращают перечисленные значения. Все остальные типы узлов возвращают пустую строку. 

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
* Класс [XmlTextReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)