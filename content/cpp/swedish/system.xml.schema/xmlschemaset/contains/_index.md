---
title: Contains()
second_title: Aspose.Slides för C++ API-referens
description: Indikerar om ett XML Schema definition language (XSD) schema med den angivna target namespace URI finns i XmlSchemaSet.
type: docs
weight: 196
url: /sv/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) metod


Anger om ett XML [Schema](../../) definition language (XSD) schema med det angivna target namespace URI finns i [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | Schemat **targetNamespace**-egenskapen. |

### Returvärde

**true** om ett schema med det angivna target namespace URI finns i [XmlSchemaSet](../); annars **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) metod


Anger om det angivna XML [Schema](../../) definition language (XSD) [XmlSchema](../../xmlschema/)-objektet finns i [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | [XmlSchema](../../xmlschema/)-objektet. |

### Returvärde

**true** om [XmlSchema](../../xmlschema/)-objektet finns i [XmlSchemaSet](../); annars **false**.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [String](../../../system/string/)
* Klass [XmlSchemaSet](../)
* Klass [XmlSchema](../../xmlschema/)
* Namnrymd [System::Xml::Schema](../../)
* Bibliotek [Aspose.Slides](../../../)