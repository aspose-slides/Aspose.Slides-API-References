---
title: Add()
second_title: Aspose.Slides для C++ справка API
description: Добавляет схему, расположенную по указанному URL, в коллекцию схем.
type: docs
weight: 40
url: /ru/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) метод

Добавляет схему, расположенную по указанному URL, в коллекцию схем.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI пространства имен, связанное со схемой. Для XML Schemas, это обычно **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | URL, указывающий схему для загрузки. |

### Возвращаемое значение

[XmlSchema](../../xmlschema/) добавлен в коллекцию схем; **nullptr**, если добавляемая схема является XDR схемой или в схеме имеются ошибки компиляции.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) метод

Добавляет схему, содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в коллекцию схем.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI пространства имен, связанное со схемой. Для XML Schemas, это обычно **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) содержащий схему для добавления. |

### Возвращаемое значение

[XmlSchema](../../xmlschema/) добавлен в коллекцию схем; **nullptr**, если добавляемая схема является XDR схемой или в схеме имеются ошибки компиляции.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Добавляет схему, содержащуюся в [XmlReader](../../../system.xml/xmlreader/), в коллекцию схем. Указанный [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых внешних ресурсов.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | URI пространства имен, связанное со схемой. Для XML Schemas, это обычно **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) содержащий схему для добавления. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения пространств имен, указанных в элементах **include** и **import** или атрибуте **x-schema** (XDR схемы). Если **nullptr**, внешние ссылки не разрешаются. |

### Возвращаемое значение

[XmlSchema](../../xmlschema/) добавлен в коллекцию схем; **nullptr**, если добавляемая схема является XDR схемой или в схеме имеются ошибки компиляции.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) метод

Добавляет [XmlSchema](../../xmlschema/) в коллекцию.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) для добавления в коллекцию. |

### Возвращаемое значение

Объект [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) метод

Добавляет [XmlSchema](../../xmlschema/) в коллекцию. Указанный [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения любых внешних ссылок.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) для добавления в коллекцию. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | [XmlResolver](../../../system.xml/xmlresolver/) используется для разрешения пространств имен, указанных в элементах **include** и **import**. Если **nullptr**, внешние ссылки не разрешаются. |

### Возвращаемое значение

[XmlSchema](../../xmlschema/) добавлен в коллекцию схем.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) метод

Добавляет все пространства имен, определённые в заданной коллекции (включая их связанные схемы), в эту коллекцию.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../), который вы хотите добавить в эту коллекцию. |

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [XmlSchema](../../xmlschema/)
* Класс [String](../../../system/string/)
* Класс [XmlSchemaCollection](../)
* Класс [XmlReader](../../../system.xml/xmlreader/)
* Класс [XmlResolver](../../../system.xml/xmlresolver/)
* Пространство имен [System::Xml::Schema](../../)
* Библиотека [Aspose.Slides](../../../)