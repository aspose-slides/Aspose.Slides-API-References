---
title: IsDerivedFrom()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie une valeur indiquant si le type de schéma dérivé spécifié est dérivé du type de schéma de base spécifié.
type: docs
weight: 209
url: /fr/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) method

Renvoie une valeur indiquant si le type de schéma dérivé spécifié est dérivé du type de schéma de base spécifié.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | Le [XmlSchemaType](../) dérivé à tester. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | Le [XmlSchemaType](../) de base contre lequel tester le [XmlSchemaType](../) dérivé. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | L’une des valeurs XmlSchemaDerivationMethod représentant une méthode de dérivation de type à exclure du test. |

### Valeur de retour

**true** si le type dérivé est dérivé du type de base ; sinon, **false**.

## Voir aussi

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchemaType](../)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)