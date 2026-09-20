---
title: PresentationLockingBehavior enumeration
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/presentationlockingbehavior/
---
## PresentationLockingBehavior enumerazione

Rappresenta il comportamento relativo al trattamento della [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) sorgente (file o **io.RawIOBase**) durante il caricamento e l'utilizzo di un'istanza di [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation).

Il tipo PresentationLockingBehavior espone i seguenti membri:

## Campi

| Campo | Descrizione |
| :- | :- |
| LOAD_AND_RELEASE | La sorgente sarà bloccata solo per il tempo di esecuzione del costruttore [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation).<br/>            Se [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) è impostato a false, tutti i BLOB<br/>            verranno caricati in memoria. Altrimenti, altri metodi come file temporanei potrebbero essere usati. Questo comportamento è più lento di [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/it/aspose.slides/presentationlockingbehavior/KEEP_LOCKED), e se è possibile passare la proprietà della sorgente a [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation), è consigliato usare [`PresentationLockingBehavior.KEEP_LOCKED`](/slides/python-net/it/aspose.slides/presentationlockingbehavior/KEEP_LOCKED). |
| KEEP_LOCKED | La sorgente sarà bloccata per l'intera durata dell'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation), fino a quando non verrà disposta.<br/>            [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/it/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) deve essere impostato a true per utilizzare<br/>            questo comportamento; altrimenti verrà generata un'eccezione. Questo comportamento è consigliato, è più veloce e consuma meno memoria rispetto a [`PresentationLockingBehavior.LOAD_AND_RELEASE`](/slides/python-net/it/aspose.slides/presentationlockingbehavior/LOAD_AND_RELEASE). |

### Osservazioni

La sorgente è il parametro passato al costruttore [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation). Nell'esempio seguente, la sorgente è il file "pres.pptx":

            Per questo esempio, la sorgente ("pres.pptx" file) sarà bloccata per una durata di [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) istanza, ovvero non potrà essere modificata o eliminata dal altro processo.

### Vedi anche
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)