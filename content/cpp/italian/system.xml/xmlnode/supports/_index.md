---
title: Supports()
second_title: Riferimento API Aspose.Slides per C++
description: Verifica se l'implementazione DOM implementa una funzionalità specifica.
type: docs
weight: 482
url: /it/system.xml/xmlnode/supports/
---
## XmlNode::Supports(String, String) metodo


Verifica se l'implementazione DOM implementa una funzionalità specifica.

```cpp
virtual bool System::Xml::XmlNode::Supports(String feature, String version)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| feature | [String](../../../system/string/) | Il nome del pacchetto della funzionalità da verificare. Questo nome non distingue tra maiuscole e minuscole. |
| version | [String](../../../system/string/) | Il numero di versione del nome del pacchetto da verificare. Se la versione non è specificata (null), il supporto a qualsiasi versione della funzionalità fa sì che il metodo restituisca true. |

### Valore restituito

**true** se la funzionalità è implementata nella versione specificata; altrimenti, **false**.
## Osservazioni



La tabella seguente descrive le combinazioni che restituiscono **true**. 

| Funzionalità | [Version](../../../system/version/)|
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |


## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)