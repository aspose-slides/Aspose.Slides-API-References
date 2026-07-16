---
title: ReadElementContentAs()
second_title: Référence API Aspose.Slides pour C++
description: Lit le contenu de l'élément comme le type demandé.
type: docs
weight: 586
url: /fr/system.xml/xmlreader/readelementcontentas/
---
## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) méthode


Lit le contenu de l'élément comme le type demandé.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Le type de la valeur à retourner. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objet [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d'espace de noms liés à la conversion de type. |

### Valeur de retour

Le contenu de l'élément converti en objet du type demandé.

## XmlReader::ReadElementContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>, String, String) méthode


Vérifie que le nom local et l'URI d'espace de noms spécifiés correspondent à ceux de l'élément actuel, puis lit le contenu de l'élément comme le type demandé.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadElementContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver, String localName, String namespaceURI)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Le type de la valeur à retourner. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objet [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) utilisé pour résoudre les préfixes d'espace de noms liés à la conversion de type. |
| localName | [String](../../../system/string/) | Le nom local de l'élément. |
| namespaceURI | [String](../../../system/string/) | L'URI d'espace de noms de l'élément. |

### Valeur de retour

Le contenu de l'élément converti en objet du type demandé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)