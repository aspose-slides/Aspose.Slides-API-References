---
title: InsertAfter()
second_title: Aspose.Slides для C++ справка API
description: Возвращает объект XmlWriter, используемый для создания нового соседнего узла после текущего выбранного узла.
type: docs
weight: 898
url: /ru/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() метод

Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового соседнего узла после текущего выбранного узла.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Возвращаемое значение

Объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового соседнего узла после текущего выбранного узла.

## XPathNavigator::InsertAfter(String) метод

Создаёт новый соседний узел после текущего выбранного узла, используя указанную XML-строку.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Строка XML-данных для нового соседнего узла. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) метод

Создаёт новый соседний узел после текущего выбранного узла, используя XML-содержимое указанного объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Объект [XmlReader](../../../system.xml/xmlreader/), расположенный на XML-данных нового соседнего узла. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) метод

Создаёт новый соседний узел после текущего выбранного узла, используя узлы в указанном объекте [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на узле, который будет добавлен в качестве нового соседнего узла. |

## Смотрите также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [XmlWriter](../../../system.xml/xmlwriter/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)