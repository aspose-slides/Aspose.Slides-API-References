---
title: ChangeType()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la valeur spécifiée, dont le type est l'une des représentations valides du type de schéma XML représenté par le XmlSchemaDatatype, vers le type d'exécution spécifié.
type: docs
weight: 66
url: /fr/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) méthode

Convertit la valeur spécifiée, dont le type est l'une des représentations valides du type de schéma XML représenté par le [XmlSchemaDatatype](../), vers le type d'exécution spécifié.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | La valeur d'entrée à convertir vers le type spécifié. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Le type cible vers lequel convertir la valeur d'entrée. |

### Valeur de retour

La valeur d'entrée convertie.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) méthode

Convertit la valeur spécifiée, dont le type est l'une des représentations valides du type de schéma XML représenté par le [XmlSchemaDatatype](../), vers le type d'exécution spécifié en utilisant le [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) si le [XmlSchemaDatatype](../) représente le type **xs:QName** ou un type dérivé de celui-ci.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | La valeur d'entrée à convertir vers le type spécifié. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | Le type cible vers lequel convertir la valeur d'entrée. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d'espace de noms. Ce paramètre n'est utile que si le [XmlSchemaDatatype](../) représente le type **xs:QName** ou un type dérivé de celui-ci. |

### Valeur de retour

La valeur d'entrée convertie.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [XmlSchemaDatatype](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)