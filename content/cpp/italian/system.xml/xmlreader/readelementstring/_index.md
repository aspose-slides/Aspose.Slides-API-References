---
title: ReadElementString()
second_title: Riferimento API di Aspose.Slides per C++
description: "Legge un elemento solo di testo. Tuttavia, è consigliato usare il metodo XmlReader::ReadElementContentAsString invece, perché fornisce un modo più diretto per gestire questa operazione."
type: docs
weight: 859
url: /it/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() metodo

Legge un elemento solo di testo. Tuttavia, si consiglia di utilizzare il metodo [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) invece, perché fornisce un modo più semplice per gestire questa operazione.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Valore restituito

Il testo contenuto nell'elemento che è stato letto. Una stringa vuota se l'elemento è vuoto.

## XmlReader::ReadElementString(String) metodo

Verifica che il valore [XmlReader::get_Name](../get_name/) dell'elemento trovato corrisponda alla stringa fornita prima di leggere un elemento solo di testo. Tuttavia, si consiglia di utilizzare il metodo [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) invece, perché fornisce un modo più semplice per gestire questa operazione.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | [String](../../../system/string/) | Il nome da verificare. |

### Valore restituito

Il testo contenuto nell'elemento che è stato letto. Una stringa vuota se l'elemento è vuoto.

## XmlReader::ReadElementString(String, String) metodo

Verifica che i valori [XmlReader::get_LocalName](../get_localname/) e [XmlReader::get_NamespaceURI](../get_namespaceuri/) dell'elemento trovato corrispondano alle stringhe fornite prima di leggere un elemento solo di testo. Tuttavia, si consiglia di utilizzare il metodo [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) invece, perché fornisce un modo più semplice per gestire questa operazione.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Il nome locale da verificare. |
| ns | [String](../../../system/string/) | L'URI dello spazio dei nomi da verificare. |

### Valore restituito

Il testo contenuto nell'elemento che è stato letto. Una stringa vuota se l'elemento è vuoto.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)