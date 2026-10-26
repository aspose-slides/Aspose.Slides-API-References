---
title: ParseValue()
second_title: Référence API Aspose.Slides pour C++
description: Lorsqu'elle est redéfinie dans une classe dérivée, valide la chaîne spécifiée par rapport à un type simple intégré ou défini par l'utilisateur.
type: docs
weight: 53
url: /fr/system.xml.schema/xmlschemadatatype/parsevalue/
---
## XmlSchemaDatatype::ParseValue(String, SharedPtr\<XmlNameTable\>, SharedPtr\<IXmlNamespaceResolver\>) method

Lorsqu'elle est redéfinie dans une classe dérivée, valide la **string** spécifiée par rapport à un type simple intégré ou défini par l'utilisateur.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ParseValue(String s, SharedPtr<XmlNameTable> nameTable, SharedPtr<IXmlNamespaceResolver> nsmgr)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| s | [String](../../../system/string/) | La **string** à valider par rapport au type simple. |
| nameTable | [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../../system.xml/xmlnametable/)\> | Le [XmlNameTable](../../../system.xml/xmlnametable/) à utiliser pour l'atomisation lors de l'analyse de la **string** si cet objet [XmlSchemaDatatype](../) représente le type **xs:NCName**. |
| nsmgr | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) à utiliser lors de l'analyse de la **string** si cet objet [XmlSchemaDatatype](../) représente le type **xs:QName**. |

### Valeur de retour

Un [Object](../../../system/object/) qui peut être converti en toute sécurité au type renvoyé par l'appel [XmlSchemaDatatype::get_ValueType](../get_valuetype/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XmlNameTable](../../../system.xml/xmlnametable/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XmlSchemaDatatype](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)