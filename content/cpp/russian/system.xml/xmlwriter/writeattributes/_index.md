---
title: WriteAttributes()
second_title: Aspose.Slides для C++ – справочник API
description: При переопределении в производном классе выводит все атрибуты, найденные в текущей позиции XmlReader.
type: docs
weight: 417
url: /ru/system.xml/xmlwriter/writeattributes/
---
## XmlWriter::WriteAttributes(SharedPtr\<XmlReader\>, bool) метод

Когда переопределено в производном классе, выводит все атрибуты, найденные в текущей позиции [XmlReader](../../xmlreader/).

```cpp
virtual void System::Xml::XmlWriter::WriteAttributes(SharedPtr<XmlReader> reader, bool defattr)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | [XmlReader](../../xmlreader/), из которого копируются атрибуты. |
| defattr | **bool** | **true** чтобы скопировать атрибуты по умолчанию из [XmlReader](../../xmlreader/); в противном случае **false**. |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../../xmlreader/)
* Класс [XmlWriter](../)
* Пространство имён [System::Xml](../../)
* Library [Aspose.Slides](../../../)