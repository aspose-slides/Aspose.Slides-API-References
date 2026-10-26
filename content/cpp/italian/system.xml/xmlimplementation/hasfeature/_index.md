---
title: HasFeature()
second_title: Riferimento API di Aspose.Slides per C++
description: Verifica se l'implementazione del Document Object Model (DOM) implementa una funzionalità specifica.
type: docs
weight: 14
url: /it/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) metodo

Verifica se l'implementazione del modello Document [Object](../../../system/object/) (DOM) implementa una funzionalità specifica.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | Il nome del pacchetto della funzionalità da testare. Questo nome non distingue tra maiuscole e minuscole. |
| strVersion | const [String](../../../system/string/)\& | Questo è il numero di versione del nome del pacchetto da testare. Se la versione non è specificata (**nullptr**), supportare qualsiasi versione della funzionalità fa sì che il metodo restituisca **true**. |

### Valore di ritorno

**true** se la funzionalità è implementata nella versione specificata; altrimenti, **false**.

## Osservazioni

La tabella seguente mostra le combinazioni che fanno sì che **HasFeature** restituisca **true**. 

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XmlImplementation](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)