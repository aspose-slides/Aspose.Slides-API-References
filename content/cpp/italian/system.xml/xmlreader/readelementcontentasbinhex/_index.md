---
title: ReadElementContentAsBinHex()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge l'elemento e decodifica il contenuto BinHex.
type: docs
weight: 794
url: /it/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodo


Legge l'elemento e decodifica il contenuto **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Il buffer in cui copiare il testo risultante. Questo valore non può essere **nullptr**. |
| index | **int32_t** | L'offset nel buffer dove iniziare a copiare il risultato. |
| count | **int32_t** | Il numero massimo di byte da copiare nel buffer. Il numero effettivo di byte copiati è restituito da questo metodo. |

### Valore restituito

Il numero di byte scritti nel buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)