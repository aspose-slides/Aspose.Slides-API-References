---
title: WriteSurrogateCharEntity()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, genera e scrive l'entità del carattere surrogato per la coppia di caratteri surrogati.
type: docs
weight: 261
url: /it/system.xml/xmlwriter/writesurrogatecharentity/
---
## XmlWriter::WriteSurrogateCharEntity(char16_t, char16_t) metodo

Quando sovrascritto in una classe derivata, genera e scrive l'entità del carattere surrogato per la coppia di caratteri surrogati.

```cpp
virtual void System::Xml::XmlWriter::WriteSurrogateCharEntity(char16_t lowChar, char16_t highChar)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lowChar | char16_t | Il surrogato basso. Deve essere un valore compreso tra 0xDC00 e 0xDFFF. |
| highChar | char16_t | Il surrogato alto. Deve essere un valore compreso tra 0xD800 e 0xDBFF. |

## Vedi anche

* Classe [XmlWriter](../)
* Namespace [System::Xml](../../)
* Libreria [Aspose.Slides](../../../)