---
title: ValueAs()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie la valeur de l'élément ou de l'attribut XML validé en tant que type spécifié à l'aide de l'objet IXmlNamespaceResolver indiqué pour résoudre les préfixes d'espace de noms.
type: docs
weight: 144
url: /fr/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Renvoie la valeur validée de l'élément ou de l'attribut XML en tant que type spécifié à l'aide de l'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) spécifié pour résoudre les préfixes d'espace de noms.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | Le type dans lequel retourner la valeur validée de l'élément ou de l'attribut XML. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | L'objet [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d'espace de noms. |

### Valeur retournée

La valeur de l'élément ou de l'attribut XML validé en tant que type demandé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XmlAtomicValue](../)
* Espace de noms [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)