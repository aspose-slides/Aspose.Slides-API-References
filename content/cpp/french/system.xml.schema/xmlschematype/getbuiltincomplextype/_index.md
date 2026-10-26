---
title: GetBuiltInComplexType()
second_title: Référence de l'API Aspose.Slides pour C++
description: Retourne un XmlSchemaComplexType qui représente le type complexe intégré du type complexe spécifié.
type: docs
weight: 196
url: /fr/system.xml.schema/xmlschematype/getbuiltincomplextype/
---
## XmlSchemaType::GetBuiltInComplexType(XmlTypeCode) méthode

Renvoie un [XmlSchemaComplexType](../../xmlschemacomplextype/) qui représente le type complexe intégré du type complexe spécifié.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(XmlTypeCode typeCode)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | L'une des valeurs de XmlTypeCode représentant le type complexe. |

### Valeur de retour

Le [XmlSchemaComplexType](../../xmlschemacomplextype/) qui représente le type complexe intégré.

## XmlSchemaType::GetBuiltInComplexType(const SharedPtr\<XmlQualifiedName\>\&) méthode

Renvoie un [XmlSchemaComplexType](../../xmlschemacomplextype/) qui représente le type complexe intégré du type complexe spécifié par nom qualifié.

```cpp
static SharedPtr<XmlSchemaComplexType> System::Xml::Schema::XmlSchemaType::GetBuiltInComplexType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | Le [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) du type complexe. |

### Valeur de retour

Le [XmlSchemaComplexType](../../xmlschemacomplextype/) qui représente le type complexe intégré.

## Voir aussi

* Enum [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [XmlSchemaComplexType](../../xmlschemacomplextype/)
* classe [XmlSchemaType](../)
* classe [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* espace de noms [System::Xml::Schema](../../)
* bibliothèque [Aspose.Slides](../../../)