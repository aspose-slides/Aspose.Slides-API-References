---
title: PrependChild()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает объект XmlWriter, используемый для создания нового дочернего узла в начале списка дочерних узлов текущего узла.
type: docs
weight: 872
url: /ru/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() метод


Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового дочернего узла в начале списка дочерних узлов текущего узла.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```


### Возвращаемое значение

Объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания нового дочернего узла в начале списка дочерних узлов текущего узла.

## XPathNavigator::PrependChild(String) метод


Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя указанную строку XML.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Строка данных XML для нового дочернего узла. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) метод


Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя XML-содержимое указанного объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Объект [XmlReader](../../../system.xml/xmlreader/), расположенный на данных XML для нового дочернего узла. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) метод


Создаёт новый дочерний узел в начале списка дочерних узлов текущего узла, используя узлы указанного объекта [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на узле, который будет добавлен в качестве нового дочернего узла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlWriter](../../../system.xml/xmlwriter/)
* Класс [XPathNavigator](../)
* Класс [String](../../../system/string/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Пространство имён [System::Xml::XPath](../../)
* Библиотека [Aspose.Slides](../../../)