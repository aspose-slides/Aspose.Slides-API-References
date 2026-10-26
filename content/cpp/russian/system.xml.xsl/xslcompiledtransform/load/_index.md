---
title: Load()
second_title: Справка API Aspose.Slides для C++
description: Компилирует таблицу стилей, содержащуюся в XmlReader.
type: docs
weight: 27
url: /ru/system.xml.xsl/xslcompiledtransform/load/
---
## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&) метод


Компилирует таблицу стилей, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей. |

## XslCompiledTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) метод


Компилирует XSLT-таблицу стилей, содержащуюся в [XmlReader](../../../system.xml/xmlreader/). [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) для применения к таблице стилей. Если это **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых таблиц стилей, упомянутых в элементах XSLT **import** и **include**. Если это **nullptr**, внешние ресурсы не разрешаются. |

## XslCompiledTransform::Load(const String\&) метод


Загружает и компилирует таблицу стилей, расположенную по указанному URI.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI таблицы стилей. |

## XslCompiledTransform::Load(const String\&, const SharedPtr\<XsltSettings\>\&, const SharedPtr\<XmlResolver\>\&) метод


Загружает и компилирует XSLT-таблицу стилей, указанную URI. [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const String &stylesheetUri, const SharedPtr<XsltSettings> &settings, const SharedPtr<XmlResolver> &stylesheetResolver)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheetUri | const [String](../../../system/string/)\& | URI таблицы стилей. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\>\& | [XsltSettings](../../xsltsettings/) для применения к таблице стилей. Если это **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | const [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения URI таблицы стилей и любых таблиц стилей, упомянутых в элементах XSLT **import** и **include**. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) метод


Компилирует таблицу стилей, содержащуюся в объекте IXPathNavigable.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим таблицу стилей. |

## XslCompiledTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, SharedPtr\<XsltSettings\>, SharedPtr\<XmlResolver\>) метод


Компилирует XSLT-таблицу стилей, содержащуюся в IXPathNavigable. [XmlResolver](../../../system.xml/xmlresolver/) разрешает любые элементы XSLT **import** или **include**, а настройки XSLT определяют разрешения для таблицы стилей.

```cpp
void System::Xml::Xsl::XslCompiledTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, SharedPtr<XsltSettings> settings, SharedPtr<XmlResolver> stylesheetResolver)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Он может быть либо [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)), либо XPathDocument, содержащим таблицу стилей. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XsltSettings](../../xsltsettings/)\> | [XsltSettings](../../xsltsettings/) для применения к таблице стилей. Если это **nullptr**, применяется настройка [XsltSettings::get_Default](../../xsltsettings/get_default/). |
| stylesheetResolver | [SharedPtr](../../../system/sharedptr/)\<[XmlResolver](../../../system.xml/xmlresolver/)\> | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых таблиц стилей, упомянутых в элементах XSLT **import** и **include**. Если это **nullptr**, внешние ресурсы не разрешаются. |

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Класс [XslCompiledTransform](../)
* Класс [XsltSettings](../../xsltsettings/)
* Класс [XmlResolver](../../../system.xml/xmlresolver/)
* Класс [String](../../../system/string/)
* Класс [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Пространство имён [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)