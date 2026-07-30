---
title: XmlParserContext()
second_title: Riferimento API di Aspose.Slides per C++
description: "Inizializza una nuova istanza della classe XmlParserContext con i valori specificati XmlNameTable, XmlNamespaceManager, xml:lang e xml:space."
type: docs
weight: 261
url: /it/system.xml/xmlparsercontext/xmlparsercontext/
---
## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace) constructor


Inizializza una nuova istanza della classe [XmlParserContext](../) con i valori specificati [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang** e **xml:space**.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare per atomizzare le stringhe. Se è **nullptr**, viene utilizzata la tabella dei nomi impiegata per costruire il **nsMgr**. Per ulteriori informazioni sulle stringhe atomizzate, vedere [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Il [XmlNamespaceManager](../../xmlnamespacemanager/) da utilizzare per la ricerca delle informazioni sul namespace, oppure **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | L'ambito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valore XmlSpace che indica l'ambito **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inizializza una nuova istanza della classe [XmlParserContext](../) con i valori specificati [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), **xml:lang**, **xml:space** e la codifica.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare per atomizzare le stringhe. Se è **nullptr**, viene usata la tabella dei nomi impiegata per costruire il **nsMgr**. Per ulteriori informazioni sulle stringhe atomizzate, vedere [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Il [XmlNamespaceManager](../../xmlnamespacemanager/) da utilizzare per la lettura delle informazioni sul namespace, oppure **nullptr**. |
| xmlLang | const [String](../../../system/string/)\& | L'ambito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valore XmlSpace che indica l'ambito **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un oggetto Encoding che indica l'impostazione della codifica. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace) constructor


Inizializza una nuova istanza della classe [XmlParserContext](../) con i valori specificati [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), l'URI di base, **xml:lang**, **xml:space** e i valori del tipo di documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare per atomizzare le stringhe. Se è **nullptr**, viene usata la tabella dei nomi impiegata per costruire il **nsMgr**. Per ulteriori informazioni sulle stringhe atomizzate, vedere [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Il [XmlNamespaceManager](../../xmlnamespacemanager/) da utilizzare per la ricerca delle informazioni sul namespace, oppure **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Il nome della dichiarazione del tipo di documento. |
| pubId | const [String](../../../system/string/)\& | L'identificatore pubblico. |
| sysId | const [String](../../../system/string/)\& | L'identificatore di sistema. |
| internalSubset | const [String](../../../system/string/)\& | Il sottoinsieme DTD interno. Il sottoinsieme DTD è usato per la risoluzione delle entità, non per la convalida del documento. |
| baseURI | const [String](../../../system/string/)\& | L'URI di base per il frammento XML (la posizione da cui il frammento è stato caricato). |
| xmlLang | const [String](../../../system/string/)\& | L'ambito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valore XmlSpace che indica l'ambito **xml:space**. |

## XmlParserContext::XmlParserContext(const SharedPtr\<XmlNameTable\>\&, const SharedPtr\<XmlNamespaceManager\>\&, const String\&, const String\&, const String\&, const String\&, const String\&, const String\&, System::Xml::XmlSpace, const SharedPtr\<System::Text::Encoding\>\&) constructor


Inizializza una nuova istanza della classe [XmlParserContext](../) con i valori specificati [XmlNameTable](../../xmlnametable/), [XmlNamespaceManager](../../xmlnamespacemanager/), l'URI di base, **xml:lang**, **xml:space**, la codifica e i valori del tipo di documento.

```cpp
System::Xml::XmlParserContext::XmlParserContext(const SharedPtr<XmlNameTable> &nt, const SharedPtr<XmlNamespaceManager> &nsMgr, const String &docTypeName, const String &pubId, const String &sysId, const String &internalSubset, const String &baseURI, const String &xmlLang, System::Xml::XmlSpace xmlSpace, const SharedPtr<System::Text::Encoding> &enc)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nt | const [SharedPtr](../../../system/sharedptr/)\<[XmlNameTable](../../xmlnametable/)\>\& | Il [XmlNameTable](../../xmlnametable/) da utilizzare per atomizzare le stringhe. Se è **nullptr**, viene usata la tabella dei nomi impiegata per costruire il **nsMgr**. Per ulteriori informazioni sulle stringhe atomizzate, vedere [XmlNameTable](../../xmlnametable/). |
| nsMgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Il [XmlNamespaceManager](../../xmlnamespacemanager/) da utilizzare per la ricerca delle informazioni sul namespace, oppure **nullptr**. |
| docTypeName | const [String](../../../system/string/)\& | Il nome della dichiarazione del tipo di documento. |
| pubId | const [String](../../../system/string/)\& | L'identificatore pubblico. |
| sysId | const [String](../../../system/string/)\& | L'identificatore di sistema. |
| internalSubset | const [String](../../../system/string/)\& | Il sottoinsieme DTD interno. Il DTD è usato per la risoluzione delle entità, non per la convalida del documento. |
| baseURI | const [String](../../../system/string/)\& | L'URI di base per il frammento XML (la posizione da cui il frammento è stato caricato). |
| xmlLang | const [String](../../../system/string/)\& | L'ambito **xml:lang**. |
| xmlSpace | [System::Xml::XmlSpace](../../xmlspace/) | Un valore XmlSpace che indica l'ambito **xml:space**. |
| enc | const [SharedPtr](../../../system/sharedptr/)\<[System::Text::Encoding](../../../system.text/encoding/)\>\& | Un oggetto Encoding che indica l'impostazione della codifica. |

## Vedi anche

* Enum [XmlSpace](../../xmlspace/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNameTable](../../xmlnametable/)
* Class [XmlNamespaceManager](../../xmlnamespacemanager/)
* Class [String](../../../system/string/)
* Class [XmlParserContext](../)
* Class [Encoding](../../../system.text/encoding/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)