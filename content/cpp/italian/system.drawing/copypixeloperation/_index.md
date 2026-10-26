---
title: CopyPixelOperation
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica come il colore sorgente in un'operazione di copia di pixel viene combinato con il colore di destinazione per ottenere un colore finale.
type: docs
weight: 391
url: /it/system.drawing/copypixeloperation/
---
## CopyPixelOperation enum

Specifica come il colore sorgente in un'operazione di copia di pixel viene combinato con il colore di destinazione per ottenere un colore finale.

```cpp
enum class CopyPixelOperation
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoMirrorBitmap | n/a | La bitmap non è specchiata. |
| Blackness | 66 | La regione di destinazione viene riempita usando il colore con indice 0 nella palette fisica. |
| NotSourceErase | 1114278 | I colori sorgente e di destinazione vengono ORati e il colore risultante viene poi invertito. |
| NotSourceCopy | 3342344 | La regione sorgente viene invertita e poi copiata nella destinazione. |
| SourceErase | 4457256 | I colori invertiti della regione di destinazione vengono ANDati con i colori della regione sorgente. |
| DestinationInvert | 5570569 | La regione di destinazione è invertita. |
| PatInvert | 5898313 | I colori del pennello attualmente selezionato nel contesto del dispositivo di destinazione vengono XORati con i colori della destinazione. |
| SourceInvert | 6684742 | I colori delle regioni sorgente e destinazione vengono XORati. |
| SourceAnd | 8913094 | I colori delle regioni sorgente e destinazione vengono ANDati. |
| MergePaint | 12255782 | I colori della regione sorgente invertita vengono ORati con i colori della regione di destinazione. |
| MergeCopy | 12583114 | I colori della regione sorgente vengono ANDati con i colori del pennello selezionato nel contesto del dispositivo di destinazione. |
| SourceCopy | 13369376 | La regione sorgente è copiata direttamente nella regione di destinazione. |
| SourcePaint | 15597702 | I colori delle regioni sorgente e destinazione vengono ORati. |
| PatCopy | 15728673 | Il pennello attualmente selezionato nel contesto del dispositivo di destinazione è copiato nella bitmap di destinazione. |
| PatPaint | 16452105 | I colori del pennello attualmente selezionato nel contesto del dispositivo di destinazione sono ORati con i colori della regione sorgente invertita. Il risultato di questa operazione è ORato con i colori della regione di destinazione. |
| Whiteness | 16711778 | La regione di destinazione viene riempita usando il colore con indice 1 nella palette fisica. |
| CaptureBlt | 1073741824 | [Windows](../../system.windows/) che sono stratificate sopra la finestra dell'applicazione sono incluse nell'immagine risultante. |

## Vedi anche

* Spazio dei nomi [System::Drawing](../)
* Libreria [Aspose.Slides](../../)