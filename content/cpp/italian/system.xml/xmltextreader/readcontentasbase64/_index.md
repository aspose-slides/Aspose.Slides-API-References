---
title: ReadContentAsBase64()
second_title: Riferimento API di Aspose.Slides per C++
description: Legge il contenuto e restituisce i byte binari decodificati in Base64.
type: docs
weight: 638
url: /it/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodo

Legge il contenuto e restituisce i byte binari decodificati in **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Il buffer in cui copiare il testo risultante. Questo valore non può essere **nullptr**. |
| index | **int32_t** | L'offset nel buffer da cui iniziare a copiare il risultato. |
| count | **int32_t** | Il numero massimo di byte da copiare nel buffer. Il numero effettivo di byte copiati è restituito da questo metodo. |

### Valore di ritorno

Il numero di byte scritti nel buffer.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)