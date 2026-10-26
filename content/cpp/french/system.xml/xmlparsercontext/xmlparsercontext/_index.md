---
title: XmlParserContext()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Initialise une nouvelle instance de la classe XmlParserContext avec les valeurs spécifiées de XmlNameTable, XmlNamespaceManager, xml:lang et xml:space."
type: docs
weight: 261
url: /fr/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor

Initialise une nouvelle instance de la classe [XmlParserContext](../) avec les valeurs [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** et **xml:space** spécifiées.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser pour atomiser les chaînes. Si c’est **nullptr**, la table de noms utilisée pour construire le **nsMgr** est utilisée à la place. Pour plus d’informations sur les chaînes atomisées, voir [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Le [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour rechercher les informations d’espace de noms, ou **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | La portée **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Une valeur XmlSpace indiquant la portée **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Initialise une nouvelle instance de la classe [XmlParserContext](../) avec les valeurs [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** et l’encodage.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser pour atomiser les chaînes. Si c’est **nullptr**, la table de noms utilisée pour construire le **nsMgr** est utilisée à la place. Pour plus d’informations sur les chaînes atomisées, voir [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Le [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour rechercher les informations d’espace de noms, ou **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | La portée **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Une valeur XmlSpace indiquant la portée **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un objet Encoding indiquant le paramètre d’encodage. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor

Initialise une nouvelle instance de la classe [XmlParserContext](../) avec les valeurs [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), l’URI de base, **xml:lang**, **xml:space** et les valeurs de type de document.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser pour atomiser les chaînes. Si c’est **nullptr**, la table de noms utilisée pour construire le **nsMgr** est utilisée à la place. Pour plus d’informations sur les chaînes atomisées, voir [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Le [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour rechercher les informations d’espace de noms, ou **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Le nom de la déclaration de type de document. |
| pubId | const [String](../../../system/string/)\& | L’identifiant public. |
| sysId | const [String](../../../system/string/)\& | L’identifiant système. |
| internalSubset | const [String](../../../system/string/)\& | Le sous-ensemble DTD interne. Le sous-ensemble DTD est utilisé pour la résolution des entités, pas pour la validation du document. |
| baseURI | const [String](../../../system/string/)\& | L’URI de base pour le fragment XML (l’emplacement d’où le fragment a été chargé). |
| xmlLang | const [String](../../../system/string/)\& | La portée **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Une valeur XmlSpace indiquant la portée **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor

Initialise une nouvelle instance de la classe [XmlParserContext](../) avec les valeurs [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), l’URI de base, **xml:lang**, **xml:space**, l’encodage et les valeurs de type de document.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Le [XmlNameTable](../../xmlnametable/) à utiliser pour atomiser les chaînes. Si c’est **nullptr**, la table de noms utilisée pour construire le **nsMgr** est utilisée à la place. Pour plus d’informations sur les chaînes atomisées, voir [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Le [XmlNamespaceManager](../../xmlnamespacemanager/) à utiliser pour rechercher les informations d’espace de noms, ou **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Le nom de la déclaration de type de document. |
| pubId | const [String](../../../system/string/)\& | L’identifiant public. |
| sysId | const [String](../../../system/string/)\& | L’identifiant système. |
| internalSubset | const [String](../../../system/string/)\& | Le sous-ensemble DTD interne. Le DTD est utilisé pour la résolution des entités, pas pour la validation du document. |
| baseURI | const [String](../../../system/string/)\& | L’URI de base pour le fragment XML (l’emplacement d’où le fragment a été chargé). |
| xmlLang | const [String](../../../system/string/)\& | La portée **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Une valeur XmlSpace indiquant la portée **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un objet Encoding indiquant le paramètre d’encodage. |

## Voir aussi

* Énumération [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNameTable](../../xmlnametable/)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Classe [String](../../../system/string/)
* Classe [XmlParserContext](../)
* Classe [Encoding](../../../system.text/encoding/)
* Espace de noms [System::Xml](../../)
* Bibliothèque [Aspose.Slides](../../../)