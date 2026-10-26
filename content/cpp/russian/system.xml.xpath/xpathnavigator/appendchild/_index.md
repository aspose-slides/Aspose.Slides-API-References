---
title: AppendChild()
second_title: Aspose.Slides for C++ справочник API
description: Возвращает объект XmlWriter, используемый для создания одного или нескольких новых дочерних узлов в конце списка дочерних узлов текущего узла.
type: docs
weight: 885
url: /ru/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() метод

Возвращает объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания одного или более новых дочерних узлов в конце списка дочерних узлов текущего узла.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Возвращаемое значение

Объект [XmlWriter](../../../system.xml/xmlwriter/), используемый для создания новых дочерних узлов в конце списка дочерних узлов текущего узла.

## XPathNavigator::AppendChild(String) метод

Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя указанную строку XML-данных.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Строка XML-данных для нового дочернего узла. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) метод

Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя содержимое XML из указанного объекта [XmlReader](../../../system.xml/xmlreader/).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Объект [XmlReader](../../../system.xml/xmlreader/), расположенный на XML-данных нового дочернего узла. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) метод

Создаёт новый дочерний узел в конце списка дочерних узлов текущего узла, используя узлы из указанного [XPathNavigator](../).

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Объект [XPathNavigator](../), расположенный на узле, который будет добавлен в качестве нового дочернего узла. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)