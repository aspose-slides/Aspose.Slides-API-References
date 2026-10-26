---
title: InsertBefore()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект XmlWriter, используемый для создания нового узла-сиблинга перед текущим выбранным узлом.
type: docs
weight: 911
url: /ru/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() метод

Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового узла-сиблинга перед текущим выбранным узлом.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Возвращаемое значение

Объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового узла-сиблинга перед текущим выбранным узлом.

## XPathNavigator::InsertBefore(String) метод

Создаёт новый узел-сиблинга перед текущим выбранным узлом, используя указанный XML-строку.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | XML-строка данных для нового узла-сиблинга. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) метод

Создаёт новый узел-сиблинга перед текущим выбранным узлом, используя содержимое XML объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Объект [XmlReader](../../../system.xml/xmlreader/), расположенный на XML-данных нового узла-сиблинга. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) метод

Создаёт новый узел-сиблинга перед текущим выбранным узлом, используя узлы из указанного [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на узле, который будет добавлен в качестве нового узла-сиблинга. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlWriter](../../../system.xml/xmlwriter/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)