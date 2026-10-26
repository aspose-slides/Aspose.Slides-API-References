---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает квалифицированное имя текущего узла.
type: docs
weight: 14
url: /ru/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() метод


Возвращает квалифицированное имя текущего узла.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Возвращаемое значение

Квалифицированное имя текущего узла. Например, **Name** равно **bk:book** для элемента **<bk:book>**.
## Примечания



Возвращаемое имя зависит от значения [XmlNodeReader::get_NodeType](../get_nodetype/) узла. Следующие типы узлов возвращают указанные значения. Все остальные типы узлов возвращают пустую строку. 

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
* Класс [XmlNodeReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)