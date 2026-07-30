---
title: Add()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge i sottotitoli chiusi WebVTT alla fine della collezione.
type: docs
weight: 27
url: /it/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) metodo


Aggiunge i sottotitoli WebVTT chiusi alla fine della collezione.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | L'etichetta dei sottotitoli chiusi. |
| filePath | [System::String](../../../system/string/) | Il percorso del file WebVTT. |

### Valore di ritorno

L'istanza [ICaptions](../../icaptions/) aggiunta.

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) metodo


Aggiunge i sottotitoli WebVTT chiusi alla fine della collezione da un flusso.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | L'etichetta dei sottotitoli chiusi. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Il flusso di input contenente dati in formato WebVTT. |

### Valore di ritorno

L'istanza [ICaptions](../../icaptions/) aggiunta.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ICaptions](../../icaptions/)
* Classe [String](../../../system/string/)
* Classe [ICaptionsCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)