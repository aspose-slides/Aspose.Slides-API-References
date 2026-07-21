---
title: Load()
second_title: Aspose.Slides для C++ справочник API
description: Загружает таблицу стилей XSLT, содержащуюся в XmlReader.
type: docs
weight: 27
url: /ru/system.xml.xsl/xsltransform/load/
---
## XslTransform::Load(const SharedPtr\<XmlReader\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей XSLT. |

## XslTransform::Load(const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в [XmlReader](../../../system.xml/xmlreader/).

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<XmlReader> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Объект [XmlReader](../../../system.xml/xmlreader/), содержащий таблицу стилей XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если он **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) либо XPathDocument, содержащий таблицу стилей XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::IXPathNavigable\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в IXPathNavigable.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::IXPathNavigable> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)\>\& | Объект, реализующий интерфейс IXPathNavigable. Это может быть [XmlNode](../../../system.xml/xmlnode/) (обычно [XmlDocument](../../../system.xml/xmldocument/)) либо XPathDocument, содержащий таблицу стилей XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если он **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Объект XPathNavigator, содержащий таблицу стилей XSLT. |

## XslTransform::Load(const SharedPtr\<System::Xml::XPath::XPathNavigator\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Загружает таблицу стилей XSLT, содержащуюся в XPathNavigator.

```cpp
void System::Xml::Xsl::XslTransform::Load(const SharedPtr<System::Xml::XPath::XPathNavigator> &stylesheet, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stylesheet | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\>\& | Объект XPathNavigator, содержащий таблицу стилей XSLT. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если он **nullptr**, внешние ресурсы не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## XslTransform::Load(const String\&) метод

Загружает таблицу стилей XSLT, указанную URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, указывающий таблицу стилей XSLT для загрузки. |

## XslTransform::Load(const String\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Загружает таблицу стилей XSLT, указанную URL.

```cpp
void System::Xml::Xsl::XslTransform::Load(const String &url, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| url | const [String](../../../system/string/)\& | URL, указывающий таблицу стилей XSLT для загрузки. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для загрузки таблицы стилей и любых таблиц стилей, указанных в элементах **xsl:import** и **xsl:include**. Если он **nullptr**, используется значение по умолчанию [XmlUrlResolver](../../../system.xml/xmlurlresolver/) без учётных данных пользователя. Значение по умолчанию [XmlUrlResolver](../../../system.xml/xmlurlresolver/) не используется для разрешения внешних ресурсов в таблице стилей, поэтому элементы **xsl:import** и **xsl:include** не разрешаются. [XmlResolver](../../../system.xml/xmlresolver/) не кэшируется после завершения этого метода. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Класс [XslTransform](../)
* Класс [XmlResolver](../../../system.xml/xmlresolver/)
* Класс [IXPathNavigable](../../../system.xml.xpath/ixpathnavigable/)
* Класс [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Класс [String](../../../system/string/)
* Пространство имен [System::Xml::Xsl](../../)
* Библиотека [Aspose.Slides](../../../)