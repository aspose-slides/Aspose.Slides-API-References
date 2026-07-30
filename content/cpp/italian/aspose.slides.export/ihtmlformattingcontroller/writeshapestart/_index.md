---
title: WriteShapeStart()
second_title: Riferimento API di Aspose.Slides per C++
description: Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento HTML aggiunto inserito e una nuova immagine sarà avviata sopra la precedente.
type: docs
weight: 53
url: /it/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metodo

Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente sarà terminata, il frammento HTML aggiunto inserito e una nuova immagine sarà avviata sopra la precedente.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Oggetto di output. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) che sta per essere renderizzata. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHtmlGenerator](../../ihtmlgenerator/)
* Classe [IShape](../../../aspose.slides/ishape/)
* Classe [IHtmlFormattingController](../)
* Namespace [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)