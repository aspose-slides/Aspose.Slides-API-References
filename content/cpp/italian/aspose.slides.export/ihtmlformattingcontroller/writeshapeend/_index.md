---
title: WriteShapeEnd()
second_title: Aspose.Slides per C++ Riferimento API
description: Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente verrà terminata, il frammento HTML aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.
type: docs
weight: 66
url: /it/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metodo

Chiamato prima del rendering della forma. Chiamato una volta per ciascuna forma. Se questa funzione scrive qualcosa sul generatore, la generazione dell'immagine della diapositiva corrente verrà terminata, il frammento HTML aggiunto verrà inserito e una nuova immagine verrà avviata sopra la precedente.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
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
* Classe [IHtmlFormattingController](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)