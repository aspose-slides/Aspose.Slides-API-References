---
title: WriteSurrogateCharEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Genera e scrive l'entità di carattere surrogate per la coppia di caratteri surrogate.
type: docs
weight: 391
url: /it/system.xml/xmltextwriter/writesurrogatecharentity/
---
## XmlTextWriter::WriteSurrogateCharEntity(char16_t, char16_t) metodo

Genera e scrive l'entità di carattere surrogate per la coppia di caratteri surrogate.

```cpp
void System::Xml::XmlTextWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowChar | char16_t | Il surrogate basso. Deve essere un valore compreso tra **0xDC00** e **0xDFFF**. |
| highChar | char16_t | Il surrogate alto. Deve essere un valore compreso tra **0xD800** e **0xDBFF**. |

## Vedi anche

* Classe [XmlTextWriter](../)
* Spazio dei nomi [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)