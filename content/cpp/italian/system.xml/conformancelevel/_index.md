---
title: ConformanceLevel
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica la quantità di verifica di input o output che gli oggetti XmlReader e XmlWriter eseguono.
type: docs
weight: 625
url: /it/system.xml/conformancelevel/
---
## ConformanceLevel enumerazione

Specifica la quantità di verifica di input o output eseguita dagli oggetti [XmlReader](../xmlreader/) e [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Auto | 0 | Il [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/) rileva automaticamente se deve essere eseguita la verifica a livello di documento o a livello di frammento, e effettua la verifica appropriata. Se stai avvolgendo un altro oggetto [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/), l'oggetto esterno non esegue alcuna verifica di conformità aggiuntiva. La verifica di conformità è lasciata all'oggetto sottostante. |
| Fragment | 1 | I dati XML sono un [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), come definito dal W3C. Questo livello di conformità rappresenta un documento XML che potrebbe non avere un elemento radice ma è comunque ben formato. Questo livello di verifica garantisce che lo stream letto o scritto possa essere consumato da qualsiasi processore come un [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | I dati XML rispettano le regole per un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) ben formato, come definito dal W3C. Questo livello di verifica garantisce che lo stream letto o scritto possa essere consumato da qualsiasi processore come un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Vedi anche

* Spazio dei nomi [System::Xml](../)
* Libreria [Aspose.Slides](../../)