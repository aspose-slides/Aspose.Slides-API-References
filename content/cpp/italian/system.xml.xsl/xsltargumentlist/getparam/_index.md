---
title: GetParam()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il parametro associato al nome qualificato dello spazio dei nomi.
type: docs
weight: 14
url: /it/system.xml.xsl/xsltargumentlist/getparam/
---
## XsltArgumentList::GetParam(const String\&, const String\&) metodo

Restituisce il parametro associato al nome qualificato dello spazio dei nomi.

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::GetParam(const String &name, const String &namespaceUri)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome del parametro. [XsltArgumentList](../) non verifica che il nome fornito sia un nome locale valido; tuttavia, il nome non può essere **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi associato al parametro. |

### Valore di ritorno

L'oggetto parametro o **nullptr** se non è stato trovato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XsltArgumentList](../)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Libreria [Aspose.Slides](../../../)