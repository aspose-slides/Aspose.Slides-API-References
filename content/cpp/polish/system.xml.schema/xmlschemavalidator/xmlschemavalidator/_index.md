---
title: XmlSchemaValidator()
second_title: Aspose.Slides dla C++ – referencja API
description: Inicjalizuje nową instancję klasy XmlSchemaValidator.
type: docs
weight: 92
url: /pl/system.xml.schema/xmlschemavalidator/xmlschemavalidator/
---
## XmlSchemaValidator::XmlSchemaValidator(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlSchemaSet\>\&, const SharedPtr\<IXmlNamespaceResolver\>\&, XmlSchemaValidationFlags) constructor


Inicjalizuje nową instancję klasy [XmlSchemaValidator](../).

```cpp
System::Xml::Schema::XmlSchemaValidator::XmlSchemaValidator(const SharedPtr<XmlNameTable> &nameTable, const SharedPtr<XmlSchemaSet> &schemas, const SharedPtr<IXmlNamespaceResolver> &namespaceResolver, XmlSchemaValidationFlags validationFlags)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nameTable | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\>\& | Obiekt [XmlNameTable](../../../system.xml/xmlnametable/) zawierający nazwy elementów i atrybutów jako atomizowane ciągi znaków. |
| schemas | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaSet](../../xmlschemaset/)\>\& | Obiekt [XmlSchemaSet](../../xmlschemaset/) zawierający schematy XML [Schema](../../) Definition Language (XSD) używane do walidacji. |
| namespaceResolver | const [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\>\& | Obiekt [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) używany do rozwiązywania przestrzeni nazw napotkanych podczas walidacji. |
| validationFlags | [XmlSchemaValidationFlags](../../xmlschemavalidationflags/) | Wartość XmlSchemaValidationFlags określająca opcje walidacji schematu. |

## Zobacz także

* Wyliczenie [XmlSchemaValidationFlags](../../xmlschemavalidationflags/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNameTable](../../../system.xml/xmlnametable/)
* Klasa [XmlSchemaSet](../../xmlschemaset/)
* Klasa [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Klasa [XmlSchemaValidator](../)
* Przestrzeń nazw [System::Xml::Schema](../../)
* Biblioteka [Aspose.Slides](../../../)