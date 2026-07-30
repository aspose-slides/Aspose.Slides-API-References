---
title: CreateDocumentType()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un nuovo oggetto XmlDocumentType.
type: docs
weight: 313
url: /it/system.xml/xmldocument/createdocumenttype/
---
## XmlDocument::CreateDocumentType(const String&, const String&, const String&, const String&) metodo


Restituisce un nuovo [XmlDocumentType](../../xmldocumenttype/) oggetto.

```cpp
virtual SharedPtr<XmlDocumentType> System::Xml::XmlDocument::CreateDocumentType(const String &name, const String &publicId, const String &systemId, const String &internalSubset)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)& | Nome del tipo di documento. |
| publicId | const [String](../../../system/string/)& | L'identificatore pubblico del tipo di documento o **nullptr**. È possibile specificare un URI pubblico e anche un identificatore di sistema per identificare la posizione del sottoinsieme DTD esterno. |
| systemId | const [String](../../../system/string/)& | L'identificatore di sistema del tipo di documento o **nullptr**. Specifica l'URL della posizione del file per il sottoinsieme DTD esterno. |
| internalSubset | const [String](../../../system/string/)& | Il sottoinsieme interno DTD del tipo di documento o **nullptr**. |

### Valore di ritorno

Il nuovo [XmlDocumentType](../../xmldocumenttype/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlDocumentType](../../xmldocumenttype/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)