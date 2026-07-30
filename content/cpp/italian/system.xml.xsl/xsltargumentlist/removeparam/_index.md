---
title: RemoveParam()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove il parametro da XsltArgumentList.
type: docs
weight: 66
url: /it/system.xml.xsl/xsltargumentlist/removeparam/
---
## XsltArgumentList::RemoveParam(const String\&, const String\&) metodo


Rimuove il parametro da [XsltArgumentList](../).

```cpp
SharedPtr<Object> System::Xml::Xsl::XsltArgumentList::RemoveParam(const String &name, const String &namespaceUri)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Il nome del parametro da rimuovere. [XsltArgumentList](../) non verifica che il nome fornito sia un nome locale valido; tuttavia, il nome non può essere **nullptr**. |
| namespaceUri | const [String](../../../system/string/)\& | L'URI di namespace del parametro da rimuovere. |

### Valore di ritorno

L'oggetto parametro o **nullptr** se non è stato trovato.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XsltArgumentList](../)
* Spazio dei nomi [System::Xml::Xsl](../../)
* Library [Aspose.Slides](../../../)