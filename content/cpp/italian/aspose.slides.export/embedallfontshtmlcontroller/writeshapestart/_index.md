---
title: WriteShapeStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Chiamato prima del rendering della forma. Chiamato una volta per ogni forma. Se questa funzione scrive qualcosa al generatore, la generazione dell'immagine della diapositiva corrente sarà completata, il frammento HTML aggiunto inserito e una nuova immagine verrà avviata sopra la precedente.
type: docs
weight: 66
url: /it/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method


Chiamato prima del rendering della forma. Chiamato una volta per ogni forma. Se questa funzione scrive qualcosa al generatore, la generazione dell'immagine della diapositiva corrente sarà completata, il frammento HTML aggiunto inserito e una nuova immagine verrà avviata sopra la precedente.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Oggetto di output. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) che sta per essere renderizzato. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)