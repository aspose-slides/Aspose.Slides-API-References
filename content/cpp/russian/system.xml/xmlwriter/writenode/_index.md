---
title: WriteNode()
second_title: Справочник API Aspose.Slides для C++
description: При переопределении в производном классе копирует всё из читателя в писатель и перемещает читатель к началу следующего соседнего узла.
type: docs
weight: 430
url: /ru/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) метод

When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | The [XmlReader](../../xmlreader/) to read from. |
| defattr | **bool** | **true** to copy the default attributes from the [XmlReader](../../xmlreader/); otherwise, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) метод

Copies everything from the XPathNavigator object to the writer. The position of the XPathNavigator remains unchanged.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | The XPathNavigator to copy from. |
| defattr | **bool** | **true** to copy the default attributes; otherwise, **false**. |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../../xmlreader/)
* Класс [XmlWriter](../)
* Класс [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)