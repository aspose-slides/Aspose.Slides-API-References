---
title: ReadValueChunk()
second_title: Riferimento API Aspose.Slides per C++
description: Legge grandi flussi di testo incorporati in un documento XML.
type: docs
weight: 807
url: /it/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) metodo

Legge grandi flussi di testo incorporati in un documento XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | L'array di caratteri che funge da buffer su cui vengono scritti i contenuti di testo. Questo valore non può essere **nullptr**. |
| index | **int32_t** | L'offset all'interno del buffer dove il [XmlReader](../) può iniziare a copiare i risultati. |
| count | **int32_t** | Il numero massimo di caratteri da copiare nel buffer. Il numero effettivo di caratteri copiati è restituito da questo metodo. |

### Valore di ritorno

Il numero di caratteri letti nel buffer. Viene restituito il valore zero quando non c'è più contenuto di testo.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)