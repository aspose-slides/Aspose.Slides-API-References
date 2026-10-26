---
title: ValidateElement()
second_title: Référence API Aspose.Slides pour C++
description: Valide l'élément dans le contexte actuel.
type: docs
weight: 131
url: /fr/system.xml.schema/xmlschemavalidator/validateelement/
---
## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) méthode

Valide l'élément dans le contexte actuel.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément à valider. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI de l'espace de noms de l'élément à valider. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies lors de la validation réussie du nom de l'élément. Ce paramètre peut être **nullptr**. |

## XmlSchemaValidator::ValidateElement(const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&, const String\&, const String\&, const String\&, const String\&) méthode

Valide l'élément dans le contexte actuel avec les valeurs d'attribut **xsi:Type**, **xsi:Nil**, **xsi:SchemaLocation** et **xsi:NoNamespaceSchemaLocation** spécifiées.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateElement(const String &localName, const String &namespaceUri, const SharedPtr<XmlSchemaInfo> &schemaInfo, const String &xsiType, const String &xsiNil, const String &xsiSchemaLocation, const String &xsiNoNamespaceSchemaLocation)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | Le nom local de l'élément à valider. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI de l'espace de noms de l'élément à valider. |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objet [XmlSchemaInfo](../../xmlschemainfo/) dont les propriétés sont définies lors de la validation réussie du nom de l'élément. Ce paramètre peut être **nullptr**. |
| xsiType | const [String](../../../system/string/)\& | La valeur d'attribut **xsi:Type** de l'élément. Ce paramètre peut être **nullptr**. |
| xsiNil | const [String](../../../system/string/)\& | La valeur d'attribut **xsi:Nil** de l'élément. Ce paramètre peut être **nullptr**. |
| xsiSchemaLocation | const [String](../../../system/string/)\& | La valeur d'attribut **xsi:SchemaLocation** de l'élément. Ce paramètre peut être **nullptr**. |
| xsiNoNamespaceSchemaLocation | const [String](../../../system/string/)\& | La valeur d'attribut **xsi:NoNamespaceSchemaLocation** de l'élément. Ce paramètre peut être **nullptr**. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaInfo](../../xmlschemainfo/)
* Classe [XmlSchemaValidator](../)
* Espace de noms [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)