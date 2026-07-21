---
title: ReadElementString()
second_title: Справочник API Aspose.Slides для C++
description: "Читает элемент, содержащий только текст. Однако рекомендуется использовать метод XmlReader::ReadElementContentAsString, так как он предоставляет более простой способ выполнения этой операции."
type: docs
weight: 859
url: /ru/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() метод

Читает элемент, содержащий только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) вместо этого, так как он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Возвращаемое значение

Текст, содержащийся в прочитанном элементе. Пустая строка, если элемент пустой.

## XmlReader::ReadElementString(String) метод

Проверяет, что значение [XmlReader::get_Name](../get_name/) найденного элемента соответствует заданной строке перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) вместо этого, так как он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | [String](../../../system/string/) | Имя для проверки. |

### Возвращаемое значение

Текст, содержащийся в прочитанном элементе. Пустая строка, если элемент пустой.

## XmlReader::ReadElementString(String, String) метод

Проверяет, что значения [XmlReader::get_LocalName](../get_localname/) и [XmlReader::get_NamespaceURI](../get_namespaceuri/) найденного элемента соответствуют заданным строкам перед чтением элемента, содержащего только текст. Однако рекомендуется использовать метод [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) вместо этого, так как он предоставляет более простой способ выполнения этой операции.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Локальное имя для проверки. |
| ns | [String](../../../system/string/) | URI пространства имён для проверки. |

### Возвращаемое значение

Текст, содержащийся в прочитанном элементе. Пустая строка, если элемент пустой.

## См. также

* Класс [String](../../../system/string/)
* Класс [XmlReader](../)
* Пространство имён [System::Xml](../../)
* Библиотека [Aspose.Slides](../../../)