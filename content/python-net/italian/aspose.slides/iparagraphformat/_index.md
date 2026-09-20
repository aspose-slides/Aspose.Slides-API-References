---
title: IParagraphFormat class
second_title: Riferimento API Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/iparagraphformat/
---
## IParagraphFormat class

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata), tutte le proprietà di questa classe sono modificabili.

Il tipo IParagraphFormat espone i seguenti membri:

## Properties

| Proprietà | Descrizione |
| :- | :- |
| [`bullet`](/slides/python-net/it/aspose.slides/iparagraphformat/bullet/) | Restituisce il formato elenco puntato del paragrafo.<br/>            Solo lettura [`IBulletFormat`](/slides/python-net/it/aspose.slides/ibulletformat). |
| [`depth`](/slides/python-net/it/aspose.slides/iparagraphformat/depth/) | Restituisce o imposta la profondità del paragrafo.<br/>            Il valore 0 indica un valore non definito.<br/>            Lettura/scrittura **int**. |
| [`alignment`](/slides/python-net/it/aspose.slides/iparagraphformat/alignment/) | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura [`TextAlignment`](/slides/python-net/it/aspose.slides/textalignment). |
| [`space_within`](/slides/python-net/it/aspose.slides/iparagraphformat/space_within/) | Restituisce o imposta la quantità di spazio tra le linee base in un paragrafo. Un valore positivo indica una percentuale, negativo la dimensione in punti. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura **float**. |
| [`space_before`](/slides/python-net/it/aspose.slides/iparagraphformat/space_before/) | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà.<br/>            Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare.<br/>            Un valore negativo specifica la dimensione dello spazio bianco in punti.<br/>            Lettura/scrittura **float**. |
| [`space_after`](/slides/python-net/it/aspose.slides/iparagraphformat/space_after/) | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà.<br/>            Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare.<br/>            Un valore negativo specifica la dimensione dello spazio bianco in punti.<br/>            Lettura/scrittura **float**. |
| [`east_asian_line_break`](/slides/python-net/it/aspose.slides/iparagraphformat/east_asian_line_break/) | Determina se il ritorno a capo dell'Est asiatico è usato in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`right_to_left`](/slides/python-net/it/aspose.slides/iparagraphformat/right_to_left/) | Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`latin_line_break`](/slides/python-net/it/aspose.slides/iparagraphformat/latin_line_break/) | Determina se il ritorno a capo latino è usato in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`hanging_punctuation`](/slides/python-net/it/aspose.slides/iparagraphformat/hanging_punctuation/) | Determina se la punteggiatura sospesa è usata in un paragrafo. Nessuna ereditarietà applicata.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`margin_left`](/slides/python-net/it/aspose.slides/iparagraphformat/margin_left/) | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/iparagraphformat/margin_right/) | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`indent`](/slides/python-net/it/aspose.slides/iparagraphformat/indent/) | Restituisce o imposta il rientro della prima riga/il rientro sospeso del paragrafo senza ereditarietà. Il rientro sospeso può essere definito con valori negativi.<br/>            Lettura/scrittura **float**. |
| [`default_tab_size`](/slides/python-net/it/aspose.slides/iparagraphformat/default_tab_size/) | Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà.<br/>            Lettura/scrittura **float**. |
| [`tabs`](/slides/python-net/it/aspose.slides/iparagraphformat/tabs/) | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata.<br/>            Solo lettura [`ITabCollection`](/slides/python-net/it/aspose.slides/itabcollection). |
| [`font_alignment`](/slides/python-net/it/aspose.slides/iparagraphformat/font_alignment/) | Restituisce o imposta un allineamento del carattere in un paragrafo senza ereditarietà.<br/>            Lettura/scrittura [`FontAlignment`](/slides/python-net/it/aspose.slides/fontalignment). |
| [`default_portion_format`](/slides/python-net/it/aspose.slides/iparagraphformat/default_portion_format/) | Restituisce il formato di porzione predefinito di un paragrafo. Nessuna ereditarietà applicata.<br/>            Solo lettura [`IPortionFormat`](/slides/python-net/it/aspose.slides/iportionformat). |

## Methods

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/iparagraphformat/get_effective/#) | Ottiene i dati di formattazione del paragrafo effective con l'ereditarietà applicata. |

### Remarks

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che
            nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori con significato "non definito".

Per ottenere i valori dei parametri di formattazione effective includendo quelli ereditati è necessario utilizzare il metodo [`IParagraphFormat.get_effective`](/slides/python-net/it/aspose.slides/iparagraphformat/get_effective) 
            che restituisce un'istanza [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata).

### See Also
* classe [`IParagraphFormatEffectiveData`](/slides/python-net/it/aspose.slides/iparagraphformateffectivedata)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)