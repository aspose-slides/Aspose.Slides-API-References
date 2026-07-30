---
title: ReadChars()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto di testo di un elemento in un buffer di caratteri. Questo metodo è progettato per leggere grandi flussi di testo incorporato chiamandolo successivamente.
type: docs
weight: 755
url: /it/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metodo

Legge il contenuto di testo di un elemento in un buffer di caratteri. Questo metodo è progettato per leggere grandi flussi di testo incorporato chiamandolo successivamente.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | L'array di caratteri che funge da buffer su cui vengono scritti i contenuti di testo. |
| index | **int32_t** | La posizione all'interno di **buffer** dove il metodo può iniziare a scrivere i contenuti di testo. |
| count | **int32_t** | Il numero di caratteri da scrivere in **buffer**. |

### Valore di ritorno

Il numero di caratteri letti. Può essere 0 se il lettore non è posizionato su un elemento o se non c'è più contenuto di testo da restituire nel contesto corrente.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlTextReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)