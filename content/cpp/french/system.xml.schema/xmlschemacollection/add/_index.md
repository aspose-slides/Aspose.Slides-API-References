---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Ajoute le schéma situé à l'URL fournie dans la collection de schémas.
type: docs
weight: 40
url: /fr/system.xml.schema/xmlschemacollection/add/
---
## XmlSchemaCollection::Add(const String\&, const String\&) méthode

Ajoute le schéma situé à l'URL donnée dans la collection de schémas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const String &uri)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms associé au schéma. Pour les schémas XML, il s'agit généralement de **targetNamespace**. |
| uri | const [String](../../../system/string/)\& | L'URL qui spécifie le schéma à charger. |

### Valeur de retour

Le [XmlSchema](../../xmlschema/) ajouté à la collection de schémas; **nullptr** si le schéma à ajouter est un schéma XDR ou s'il y a des erreurs de compilation dans le schéma.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&) méthode

Ajoute le schéma contenu dans le [XmlReader](../../../system.xml/xmlreader/) à la collection de schémas.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms associé au schéma. Pour les schémas XML, il s'agit généralement de **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Le [XmlReader](../../../system.xml/xmlreader/) contenant le schéma à ajouter. |

### Valeur de retour

Le [XmlSchema](../../xmlschema/) ajouté à la collection de schémas; **nullptr** si le schéma à ajouter est un schéma XDR ou s'il y a des erreurs de compilation dans le schéma.

## XmlSchemaCollection::Add(const String\&, const SharedPtr\<XmlReader\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode

Ajoute le schéma contenu dans le [XmlReader](../../../system.xml/xmlreader/) à la collection de schémas. Le [XmlResolver](../../../system.xml/xmlresolver/) spécifié est utilisé pour résoudre les ressources externes.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const String &ns, const SharedPtr<XmlReader> &reader, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | L'URI de l'espace de noms associé au schéma. Pour les schémas XML, il s'agit généralement de **targetNamespace**. |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\>\& | Le [XmlReader](../../../system.xml/xmlreader/) contenant le schéma à ajouter. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre les espaces de noms référencés dans les éléments **include** et **import** ou l'attribut **x-schema** (schémas XDR). Si ce résultat est **nullptr**, les références externes ne sont pas résolues. |

### Valeur de retour

Le [XmlSchema](../../xmlschema/) ajouté à la collection de schémas; **nullptr** si le schéma à ajouter est un schéma XDR ou s'il y a des erreurs de compilation dans le schéma.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&) méthode

Ajoute le [XmlSchema](../../xmlschema/) à la collection.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Le [XmlSchema](../../xmlschema/) à ajouter à la collection. |

### Valeur de retour

L'objet [XmlSchema](../../xmlschema/).

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchema\>\&, const SharedPtr\<System::Xml::XmlResolver\>\&) méthode

Ajoute le [XmlSchema](../../xmlschema/) à la collection. Le [XmlResolver](../../../system.xml/xmlresolver/) spécifié est utilisé pour résoudre les références externes.

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchema> &schema, const SharedPtr<System::Xml::XmlResolver> &resolver)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | Le [XmlSchema](../../xmlschema/) à ajouter à la collection. |
| resolver | const [SharedPtr](../../../system/sharedptr/)\<[System::Xml::XmlResolver](../../../system.xml/xmlresolver/)\>\& | Le [XmlResolver](../../../system.xml/xmlresolver/) utilisé pour résoudre les espaces de noms référencés dans les éléments **include** et **import**. Si ce résultat est **nullptr**, les références externes ne sont pas résolues. |

### Valeur de retour

Le [XmlSchema](../../xmlschema/) ajouté à la collection de schémas.

## XmlSchemaCollection::Add(const SharedPtr\<XmlSchemaCollection\>\&) méthode

Ajoute tous les espaces de noms définis dans la collection donnée (y compris leurs schémas associés) à cette collection.

```cpp
void System::Xml::Schema::XmlSchemaCollection::Add(const SharedPtr<XmlSchemaCollection> &schema)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaCollection](../)\>\& | Le [XmlSchemaCollection](../) que vous souhaitez ajouter à cette collection. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlSchema](../../xmlschema/)
* Classe [String](../../../system/string/)
* Classe [XmlSchemaCollection](../)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Classe [XmlResolver](../../../system.xml/xmlresolver/)
* Espace de noms [System::Xml::Schema](../../)
* Bibliothèque [Aspose.Slides](../../../)