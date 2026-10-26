---
title: LoadingStreamBehavior enumeration
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/loadingstreambehavior/
---
## LoadingStreamBehavior enumerazione

Il **io.RawIOBase** passato a un metodo è considerato come un Binary Large Object (BLOB) (vedi la descrizione [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)). I valori di questa enumerazione indicano come il **io.RawIOBase** deve essere trattato quando viene passato al metodo. A seconda dei requisiti, si possono prendere decisioni diverse per fornire il comportamento più efficiente.

Il tipo LoadingStreamBehavior espone i seguenti membri:

## Campi

| Campo | Descrizione |
| :- | :- |
| READ_STREAM_AND_RELEASE | Lo stream verrà letto fino alla fine e poi rilasciato - ovvero sarà garantito che questo stream <br/>            non sarà più utilizzato dall'istanza [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) in futuro. Può essere chiuso dal codice client <br/>            o utilizzato in qualsiasi altro modo. |
| KEEP_LOCKED | Lo stream verrà bloccato all'interno dell'oggetto [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation), ovvero la proprietà dello stream verrà trasferita. L'oggetto [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation) sarà responsabile di <br/>            rimuovere correttamente lo stream quando questo oggetto verrà smaltito. <br/>            Questo comportamento è estremamente utile quando è necessario serializzare un grande file BLOB (come un grande <br/>            video o audio -vedi la descrizione [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)) e si vuole impedire il caricamento <br/>            di questo file in memoria o altri problemi di prestazioni. È possibile aprire semplicemente il **System.IO.FileStream** <br/>            per questo file e passarlo a un metodo, scegliendo [`LoadingStreamBehavior.KEEP_LOCKED`](/slides/python-net/it/aspose.slides/loadingstreambehavior/KEEP_LOCKED) LoadingStreamBehavior. |

### Vedi anche
* classe [`IBlobManagementOptions`](/slides/python-net/it/aspose.slides/iblobmanagementoptions)
* classe [`IPresentation`](/slides/python-net/it/aspose.slides/ipresentation)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)