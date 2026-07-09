---
title: ParagraphFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di IParagraphFormatEffectiveData./iparagraphformateffectivedata, tutte le proprietà di questa classe sono modificabili.
type: docs
weight: 9310
url: /it/aspose.slides/paragraphformat/
---
## ParagraphFormat classe

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tutte le proprietà di questa classe sono modificabili.

```csharp
public sealed class ParagraphFormat : PVIObject, IChartParagraphFormat, IParagraphFormat
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ParagraphFormat](paragraphformat)() | Inizializza una nuova istanza della classe [`ParagraphFormat`](../paragraphformat). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.slides/paragraphformat/alignment) { get; set; } | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [`TextAlignment`](../textalignment). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Sola lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [DefaultTabSize](../../aspose.slides/paragraphformat/defaulttabsize) { get; set; } | Restituisce o imposta la dimensione di tabulazione predefinita senza ereditarietà. Lettura/scrittura Single. |
| [EastAsianLineBreak](../../aspose.slides/paragraphformat/eastasianlinebreak) { get; set; } | Determina se il ritorno a capo asiatico orientale è utilizzato in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/paragraphformat/fontalignment) { get; set; } | Restituisce o imposta un allineamento del font in un paragrafo senza ereditarietà. Lettura/scrittura [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/paragraphformat/hangingpunctuation) { get; set; } | Determina se la punteggiatura sospesa è utilizzata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/paragraphformat/indent) { get; set; } | Restituisce o imposta l'indentazione della prima riga/indentazione sospesa del paragrafo senza ereditarietà. L'indentazione sospesa può essere definita con valori negativi. Lettura/scrittura Single. |
| [LatinLineBreak](../../aspose.slides/paragraphformat/latinlinebreak) { get; set; } | Determina se il ritorno a capo latino è utilizzato in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/paragraphformat/marginleft) { get; set; } | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura Single. |
| [MarginRight](../../aspose.slides/paragraphformat/marginright) { get; set; } | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura Single. |
| [RightToLeft](../../aspose.slides/paragraphformat/righttoleft) { get; set; } | Determina se la scrittura da destra a sinistra è utilizzata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/paragraphformat/spaceafter) { get; set; } | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura Single. |
| [SpaceBefore](../../aspose.slides/paragraphformat/spacebefore) { get; set; } | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura Single. |
| [SpaceWithin](../../aspose.slides/paragraphformat/spacewithin) { get; set; } | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Valore positivo indica percentuale, negativo indica dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura Single. |
| [Tabs](../../aspose.slides/paragraphformat/tabs) { get; } | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [`ITabCollection`](../itabcollection). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| [GetEffective](../../aspose.slides/paragraphformat/geteffective)() | Ottiene i dati di formattazione del paragrafo effettivi con l'ereditarietà applicata. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Note

Questa classe è utilizzata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che non viene applicata alcuna ereditarietà durante il recupero dei valori, quindi nella maggior parte dei casi si otterranno valori che indicano "non definito".

Per ottenere i valori dei parametri di formattazione effettivi, inclusi quelli ereditati, è necessario utilizzare il metodo [`GetEffective`](./geteffective) che restituisce un'istanza [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IChartParagraphFormat](../../aspose.slides.charts/ichartparagraphformat)
* interfaccia [IParagraphFormat](../iparagraphformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->