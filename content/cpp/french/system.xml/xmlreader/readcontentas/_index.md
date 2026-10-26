---
title: ReadContentAs()
second_title: Référence API Aspose.Slides pour C++
description: Lit le contenu comme un objet du type spécifié.
type: docs
weight: 456
url: /fr/system.xml/xmlreader/readcontentas/
---
## XmlReader::ReadContentAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) méthode

Lit le contenu comme un objet du type spécifié.

```cpp
virtual SharedPtr<Object> System::Xml::XmlReader::ReadContentAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | Le type de la valeur à retourner. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../ixmlnamespaceresolver/)\> | Un objet [IXmlNamespaceResolver](../../ixmlnamespaceresolver/) qui est utilisé pour résoudre les préfixes d'espace de noms liés à la conversion de type. Par exemple, cela peut être utilisé lors de la conversion d'un objet [XmlQualifiedName](../../xmlqualifiedname/) en **xs:string**. Cette valeur peut être **nullptr**. |

### Valeur de retour

Le contenu texte concaténé ou la valeur d'attribut converti au type demandé.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [IXmlNamespaceResolver](../../ixmlnamespaceresolver/)
* Classe [XmlReader](../)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)