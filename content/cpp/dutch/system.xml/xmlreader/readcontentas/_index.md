---
title: ReadContentAs()
second_title: Aspose.Slides voor C++ API-referentie
description: Leest de inhoud als een object van het opgegeven type.
type: docs
weight: 456
url: /nl/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) methode


Leest de inhoud als een object van het opgegeven type.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Het type van de waarde die moet worden geretourneerd. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Een [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) object dat wordt gebruikt om alle namespace-prefixen met betrekking tot typeconversie op te lossen. Bijvoorbeeld, dit kan worden gebruikt bij het converteren van een [XmlQualifiedName](../../xmlqualifiedname/) object naar een **xs:string**. Deze waarde kan **nullptr** zijn. |

### Returnwaarde

De samengevoegde tekstinhoud of attribuutwaarde geconverteerd naar het aangevraagde type.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Klasse [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)