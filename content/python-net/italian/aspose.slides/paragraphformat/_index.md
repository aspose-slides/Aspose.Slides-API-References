---
title: ParagraphFormat class
second_title: Riferimento API Aspose.Slides per Python tramite .NET
description: 
type: docs
url: /it/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata), tutte le proprietà di questa classe sono modificabili.

**Ereditarietà:**[`ParagraphFormat`](/slides/python-net/it/aspose.slides/paragraphformat) → [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)

Il tipo ParagraphFormat espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/paragraphformat/__init__/#) | Inizializza una nuova istanza della classe [`ParagraphFormat`](/slides/python-net/it/aspose.slides/paragraphformat). |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`alignment`](/slides/python-net/it/aspose.slides/paragraphformat/alignment/) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura [`TextAlignment`](/slides/python-net/it/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/it/aspose.slides/paragraphformat/space_within/) | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Un valore positivo indica percentuale, un valore negativo - dimensione in punti. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura **float**. |
| [`space_before`](/slides/python-net/it/aspose.slides/paragraphformat/space_before/) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà.<br/>            Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve avere.<br/>            Un valore negativo specifica la dimensione dello spazio bianco in punti.<br/>            Lettura/scrittura **float**. |
| [`space_after`](/slides/python-net/it/aspose.slides/paragraphformat/space_after/) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà.<br/>            Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve avere.<br/>            Un valore negativo specifica la dimensione dello spazio bianco in punti.<br/>            Lettura/scrittura **float**. |
| [`east_asian_line_break`](/slides/python-net/it/aspose.slides/paragraphformat/east_asian_line_break/) | Determina se è usata la interruzione di riga East Asian in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/it/aspose.slides/paragraphformat/right_to_left/) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/it/aspose.slides/paragraphformat/latin_line_break/) | Determina se è usata l'interruzione di riga Latin in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/it/aspose.slides/paragraphformat/hanging_punctuation/) | Determina se è usata la punteggiatura sospesa in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/it/aspose.slides/paragraphformat/margin_left/) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/paragraphformat/margin_right/) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`indent`](/slides/python-net/it/aspose.slides/paragraphformat/indent/) | Restituisce o imposta l'Indentazione della Prima Riga/Indentazione Sospesa del paragrafo senza ereditarietà. L'Indentazione Sospesa può essere definita con valori negativi.<br/>            Lettura/scrittura **float**. |
| [`default_tab_size`](/slides/python-net/it/aspose.slides/paragraphformat/default_tab_size/) | Restituisce o imposta la dimensione di tabulazione predefinita senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`tabs`](/slides/python-net/it/aspose.slides/paragraphformat/tabs/) | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata.<br/>            Sola lettura [`ITabCollection`](/slides/python-net/it/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/it/aspose.slides/paragraphformat/font_alignment/) | Restituisce o imposta l'allineamento del font in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura [`FontAlignment`](/slides/python-net/it/aspose.slides/fontalignment). |
| [`slide`](/slides/python-net/it/aspose.slides/paragraphformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/paragraphformat/presentation/) |  |
| [`bullet`](/slides/python-net/it/aspose.slides/paragraphformat/bullet/) |  |
| [`depth`](/slides/python-net/it/aspose.slides/paragraphformat/depth/) |  |
| [`default_portion_format`](/slides/python-net/it/aspose.slides/paragraphformat/default_portion_format/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/paragraphformat/get_effective/#) | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |

### Osservazioni

Questa classe è utilizzata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che
            nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che significano "non definito".

Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario utilizzare il metodo [`ParagraphFormat.get_effective`](/slides/python-net/it/aspose.slides/paragraphformat/get_effective) 
            che restituisce un'istanza [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata).

### Vedi anche
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata)
* classe [`ParagraphFormat`](/slides/python-net/it/aspose.slides/paragraphformat)
* classe [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)