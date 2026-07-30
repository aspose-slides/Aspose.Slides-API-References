---
title: LoadingStreamBehavior
second_title: Riferimento API di Aspose.Slides per C++
description: "Lo Stream di System::IO::Stream passato a un metodo è considerato come un Binary Large Object (BLOB) (vedi la descrizione di IBlobManagementOptions). I valori di questa enumerazione identificano come lo Stream di System::IO::Stream dovrebbe essere trattato quando viene passato al metodo. A seconda dei requisiti, possono essere prese decisioni diverse per fornire il comportamento più efficiente."
type: docs
weight: 6735
url: /it/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enum

Il [System::IO::Stream](../../system.io/stream/) passato a un metodo è considerato come un Binary Large Object (BLOB) (vedi la descrizione di [IBlobManagementOptions](../iblobmanagementoptions/)). I valori di questa enumerazione identificano come il [System::IO::Stream](../../system.io/stream/) debba essere trattato quando viene passato al metodo. A seconda dei requisiti, possono essere prese decisioni diverse per fornire il comportamento più efficiente.

```cpp
enum class LoadingStreamBehavior
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ReadStreamAndRelease | 0 | Il flusso verrà letto fino alla fine e quindi rilasciato - cioè sarà garantito che questo flusso non sarà più utilizzato dall'istanza [IPresentation](../ipresentation/) in futuro. Può essere chiuso dal codice client o usato in qualsiasi altro modo. |
| KeepLocked | 1 | Il flusso verrà bloccato all'interno dell'oggetto [IPresentation](../ipresentation/), cioè la proprietà del flusso verrà trasferita. L'oggetto [IPresentation](../ipresentation/) sarà responsabile di eliminare correttamente il flusso quando questo oggetto verrà eliminato da solo. Questo comportamento è estremamente utile quando è necessario serializzare un grande file BLOB (come un video o audio di grandi dimensioni - vedi la descrizione di [IBlobManagementOptions](../iblobmanagementoptions/)) e si desidera evitare di caricare questo file in memoria o altri problemi di prestazioni. È sufficiente aprire il [System::IO::FileStream](../../system.io/filestream/) per questo file e passarlo a un metodo, scegliendo il LoadingStreamBehavior [LoadingStreamBehavior::KeepLocked](./). |

## Vedi anche

* Spazio dei nomi [Aspose::Slides](../)
* Libreria [Aspose.Slides](../../)