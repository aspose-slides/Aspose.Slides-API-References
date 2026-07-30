---
title: ReadContentAsBinHex()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto e restituisce i byte binari decodificati BinHex.
type: docs
weight: 781
url: /it/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodo


Legge il contenuto e restituisce i byte binari decodificati **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Il buffer in cui copiare il testo risultante. Questo valore non può essere **nullptr**. |
| index | **int32_t** | L'offset nel buffer da cui iniziare a copiare il risultato. |
| count | **int32_t** | Il numero massimo di byte da copiare nel buffer. Il numero reale di byte copiati viene restituito da questo metodo. |

### Valore di ritorno

Il numero di byte scritti nel buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)