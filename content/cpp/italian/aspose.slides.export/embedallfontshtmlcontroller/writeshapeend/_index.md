---
title: WriteShapeEnd()
second_title: Riferimento API Aspose.Slides per C++
description: Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa su generator, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine sarà avviata sopra la precedente.
type: docs
weight: 79
url: /it/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metodo

Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa su generator, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento html aggiunto sarà inserito e una nuova immagine sarà avviata sopra la precedente.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Oggetto di output. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) che è renderizzata per ultima. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [EmbedAllFontsHtmlController](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)