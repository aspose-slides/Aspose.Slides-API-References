---
title: get_ParagraphFormat()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce l'oggetto di formattazione per questo paragrafo. Sola lettura IParagraphFormat.
type: docs
weight: 14
url: /it/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() metodo

Restituisce l'oggetto di formattazione per questo paragrafo. Sola lettura [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Osservazioni

L'oggetto di formattazione contiene i parametri di formattazione definiti solo per il paragrafo corrente, i dati ereditati non sono applicati.

Per ottenere i valori effettivi includendo quelli ereditati usa il metodo [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IParagraphFormat](../../iparagraphformat/)
* Classe [Paragraph](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)