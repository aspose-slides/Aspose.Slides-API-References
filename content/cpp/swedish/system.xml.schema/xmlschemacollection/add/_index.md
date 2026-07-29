---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till schemat som finns på den angivna URL:en i schemasamlingen.
type: docs
weight: 40
url: /sv/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) metod


Lägger till schemat som finns på den angivna URL:en i schemasamlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Namespace-URI:n som är associerad med schemat. För XML-scheman är detta vanligtvis **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | URL:en som specificerar schemat som ska laddas. |

### Returvärde

Det [XmlSchema](../../xmlschema/) som lades till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) metod


Lägger till schemat som finns i [XmlReader](../../../system.xml/xmlreader/) till schemasamlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Namespace-URI:n som är associerad med schemat. För XML-scheman är detta vanligtvis **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) som innehåller schemat som ska läggas till. |

### Returvärde

Det [XmlSchema](../../xmlschema/) som lades till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod


Lägger till schemat som finns i [XmlReader](../../../system.xml/xmlreader/) till schemasamlingen. Den angivna [XmlResolver](../../../system.xml/xmlresolver/) används för att lösa eventuella externa resurser.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | Namespace-URI:n som är associerad med schemat. För XML-scheman är detta vanligtvis **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) som innehåller schemat som ska läggas till. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include**- och **import**-element eller **x-schema**-attribut (XDR-scheman). Om detta är **nullptr** löses inte externa referenser. |

### Returvärde

Det [XmlSchema](../../xmlschema/) som lades till i schemasamlingen; **nullptr** om det schema som läggs till är ett XDR-schema eller om det finns kompileringsfel i schemat.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) metod


Lägger till [XmlSchema](../../xmlschema/) till samlingen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) som ska läggas till i samlingen. |

### Returvärde

Objektet [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) metod


Lägger till [XmlSchema](../../xmlschema/) till samlingen. Den angivna [XmlResolver](../../../system.xml/xmlresolver/) används för att lösa eventuella externa referenser.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/) som ska läggas till i samlingen. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Den [XmlResolver](../../../system.xml/xmlresolver/) som används för att lösa namnrymder som refereras i **include**- och **import**-element. Om detta är **nullptr** löses inte externa referenser. |

### Returvärde

Det [XmlSchema](../../xmlschema/) som lades till i schemasamlingen.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) metod


Lägger till alla namnrymder som definierats i den angivna samlingen (inklusive deras associerade scheman) till den här samlingen.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | [XmlSchemaCollection](../) som du vill lägga till i den här samlingen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [XmlSchema](../../xmlschema/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaCollection](../)
* Klass [XmlReader](../../../system.xml/xmlreader/)
* Klass [XmlResolver](../../../system.xml/xmlresolver/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)