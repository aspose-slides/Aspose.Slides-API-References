---
title: CompareDocument()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, confronta gli Uniform Resource Identifiers (URI) di base di due documenti in base all'ordine con cui i documenti sono stati caricati dal processore XSLT (cioè la classe XslTransform).
type: docs
weight: 53
url: /it/system.xml.xsl/xsltcontext/comparedocument/
---
## XsltContext::CompareDocument(String, String) metodo

Quando sovrascritto in una classe derivata, confronta gli Uniform Resource Identifier (URI) di base di due documenti in base all'ordine con cui i documenti sono stati caricati dal processore XSLT (ovvero la classe [XslTransform](../../xsltransform/)).

```cpp
virtual int32_t System::Xml::Xsl::XsltContext::CompareDocument(String baseUri, String nextbaseUri)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseUri | [String](../../../system/string/) | L'URI di base del primo documento da confrontare. |
| nextbaseUri | [String](../../../system/string/) | L'URI di base del secondo documento da confrontare. |

### Valore restituito

Un valore intero che descrive l'ordine relativo dei due URI di base: -1 se **baseUri** si verifica prima di **nextbaseUri**; 0 se i due URI di base sono identici; e 1 se **baseUri** si verifica dopo **nextbaseUri**.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XsltContext](../)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Libreria [Aspose.Slides](../../../)