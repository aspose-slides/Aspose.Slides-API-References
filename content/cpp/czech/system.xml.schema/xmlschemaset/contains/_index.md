---
title: Contains()
second_title: Aspose.Slides pro C++ API Reference
description: Určuje, zda se v XmlSchemaSet nachází schéma XML Schema Definition Language (XSD) s určeným URI cílového jmenného prostoru.
type: docs
weight: 196
url: /cs/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metoda


Určuje, zda se XML [Schema](../../) definiční jazyk (XSD) schéma s určeným URI cílového jmenného prostoru nachází v [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Vlastnost **targetNamespace** schématu. |

### Návratová hodnota

**true** pokud se schéma s určeným URI cílového jmenného prostoru nachází v [XmlSchemaSet](../); jinak **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metoda


Určuje, zda je zadaný XML [Schema](../../) definiční jazyk (XSD) [XmlSchema](../../xmlschema/) objekt v [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Objekt [XmlSchema](../../xmlschema/). |

### Návratová hodnota

**true** pokud je objekt [XmlSchema](../../xmlschema/) v [XmlSchemaSet](../); jinak **false**.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [String](../../../system/string/)
* třída [XmlSchemaSet](../)
* třída [XmlSchema](../../xmlschema/)
* jmenný prostor [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)