---
title: XmlValidatingReader()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe XmlValidatingReader che convalida il contenuto restituito dal XmlReader fornito.
type: docs
weight: 430
url: /it/system.xml/xmlvalidatingreader/xmlvalidatingreader/
---
## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<XmlReader\>\&) costruttore

Inizializza una nuova istanza della classe [XmlValidatingReader](../) che convalida il contenuto restituito dal [XmlReader](../../xmlreader/) fornito.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<XmlReader> &reader)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\>\& | [XmlReader](../../xmlreader/) da cui leggere durante la convalida. L'implementazione corrente supporta solo [XmlTextReader](../../xmltextreader/). |

## XmlValidatingReader::XmlValidatingReader(const String\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) costruttore

Inizializza una nuova istanza della classe [XmlValidatingReader](../) con i valori specificati.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const String &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFragment | const [String](../../../system/string/)\& | La stringa contenente il frammento XML da analizzare. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Il XmlNodeType del frammento XML. Questo determina anche cosa può contenere la stringa del frammento (vedi tabella sotto). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Il [XmlParserContext](../../xmlparsercontext/) in cui il frammento XML deve essere analizzato. Include il [NameTable](../../nametable/) da usare, la codifica, l'ambito del namespace, **xml:lang** corrente e l'ambito **xml:space**. |

## Osservazioni

La tabella seguente elenca i valori validi per **fragType** e come il lettore analizza ciascuno dei diversi tipi di nodo.

| XmlNodeType | Il frammento può contenere |
| --- | --- |
| Element| Qualsiasi contenuto di elemento valido (ad esempio, qualsiasi combinazione di elementi, commenti, istruzioni di processo, cdata, testo e riferimenti a entità). |
| [Attribute](../../../system/attribute/)| Il valore di un attributo (la parte all'interno delle virgolette). |
| Document| Il contenuto di un intero documento XML; questo impone regole a livello di documento. |

## XmlValidatingReader::XmlValidatingReader(const SharedPtr\<IO::Stream\>\&, XmlNodeType, const SharedPtr\<XmlParserContext\>\&) costruttore

Inizializza una nuova istanza della classe [XmlValidatingReader](../) con i valori specificati.

```cpp
System::Xml::XmlValidatingReader::XmlValidatingReader(const SharedPtr<IO::Stream> &xmlFragment, XmlNodeType fragType, const SharedPtr<XmlParserContext> &context)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| xmlFragment | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | Il flusso contenente il frammento XML da analizzare. |
| fragType | [XmlNodeType](../../xmlnodetype/) | Il XmlNodeType del frammento XML. Questo determina cosa può contenere il frammento (vedi tabella sotto). |
| context | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | Il [XmlParserContext](../../xmlparsercontext/) in cui il frammento XML deve essere analizzato. Include il [XmlNameTable](../../xmlnametable/) da usare, la codifica, l'ambito del namespace, **xml:lang** corrente e l'ambito **xml:space**. |

## Osservazioni

La tabella seguente elenca i valori validi per **fragType** e come il lettore analizza ciascuno dei diversi tipi di nodo.

| XmlNodeType | Il frammento può contenere |
| --- | --- |
| Element| Qualsiasi contenuto di elemento valido (ad esempio, qualsiasi combinazione di elementi, commenti, istruzioni di processo, cdata, testo e riferimenti a entità). |
| [Attribute](../../../system/attribute/)| Il valore di un attributo (la parte all'interno delle virgolette). |
| Document| Il contenuto di un intero documento XML; questo impone regole a livello di documento. |

## Vedi anche

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlValidatingReader](../)
* Classe [String](../../../system/string/)
* Classe [XmlParserContext](../../xmlparsercontext/)
* Classe [Stream](../../../system.io/stream/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)