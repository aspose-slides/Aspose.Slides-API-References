---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt het schema dat zich op de opgegeven URL bevindt toe aan de schemacollectie.
type: docs
weight: 40
url: /nl/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) methode

Voegt het schema dat zich op de opgegeven URL bevindt toe aan de schemacollectie.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het schema is gekoppeld. Voor XML-schema's is dit doorgaans de **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | De URL die aangeeft welk schema moet worden geladen. |

### Retourwaarde

Het [XmlSchema](../../xmlschema/) dat aan de schemacollectie is toegevoegd; **nullptr** als het toegevoegde schema een XDR-schema is of als er compilatiefouten in het schema zijn.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) methode


Voegt het schema dat zich in de [XmlReader](../../../system.xml/xmlreader/) bevindt toe aan de schemacollectie.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het schema is gekoppeld. Voor XML-schema's is dit doorgaans de **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) die het toe te voegen schema bevat. |

### Retourwaarde

Het [XmlSchema](../../xmlschema/) dat aan de schemacollectie is toegevoegd; **nullptr** als het toegevoegde schema een XDR-schema is of als er compilatiefouten in het schema zijn.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode


Voegt het schema dat zich in de [XmlReader](../../../system.xml/xmlreader/) bevindt toe aan de schemacollectie. De opgegeven [XmlResolver](../../../system.xml/xmlresolver/) wordt gebruikt om eventuele externe bronnen op te lossen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | De namespace-URI die aan het schema is gekoppeld. Voor XML-schema's is dit doorgaans de **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | [XmlReader](../../../system.xml/xmlreader/) die het toe te voegen schema bevat. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om namespaces op te lossen die worden vermeld in **include**- en **import**-elementen of het **x-schema**-attribuut (XDR-schema's). Als dit **nullptr** is, worden externe verwijzingen niet opgelost. |

### Retourwaarde

Het [XmlSchema](../../xmlschema/) dat aan de schemacollectie is toegevoegd; **nullptr** als het toegevoegde schema een XDR-schema is of als er compilatiefouten in het schema zijn.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) methode


Voegt de [XmlSchema](../../xmlschema/) toe aan de collectie.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | De [XmlSchema](../../xmlschema/) die aan de collectie moet worden toegevoegd. |

### Retourwaarde

Het [XmlSchema](../../xmlschema/)-object.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) methode


Voegt de [XmlSchema](../../xmlschema/) toe aan de collectie. De opgegeven [XmlResolver](../../../system.xml/xmlresolver/) wordt gebruikt om eventuele externe verwijzingen op te lossen.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | De [XmlSchema](../../xmlschema/) die aan de collectie moet worden toegevoegd. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | De [XmlResolver](../../../system.xml/xmlresolver/) die wordt gebruikt om namespaces op te lossen die worden vermeld in **include**- en **import**-elementen. Als dit **nullptr** is, worden externe verwijzingen niet opgelost. |

### Retourwaarde

De [XmlSchema](../../xmlschema/) die aan de schemacollectie is toegevoegd.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) methode


Voegt alle in de opgegeven collectie gedefinieerde namespaces (inclusief hun bijbehorende schema's) toe aan deze collectie.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | De [XmlSchemaCollection](../) die u aan deze collectie wilt toevoegen. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [String](../../../system/string/)
* Class [XmlSchemaCollection](../)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Class [XmlResolver](../../../system.xml/xmlresolver/)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)