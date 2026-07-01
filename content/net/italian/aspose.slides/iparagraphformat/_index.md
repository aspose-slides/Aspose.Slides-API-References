---
title: IParagraphFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di IParagraphFormatEffectiveData./iparagraphformateffectivedata, tutte le proprietà di questa classe sono modificabili.
type: docs
weight: 6570
url: /it/aspose.slides/iparagraphformat/
---
## IParagraphFormat interfaccia

Questa classe contiene le proprietà di formattazione del paragrafo. A differenza di [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata), tutte le proprietà di questa classe sono scrivibili.

```csharp
public interface IParagraphFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Alignment](../../aspose.slides/iparagraphformat/alignment) { get; set; } | Restituisce o imposta l'allineamento del testo in un paragrafo senza ereditarietà. Lettura/scrittura [`TextAlignment`](../textalignment). |
| [Bullet](../../aspose.slides/iparagraphformat/bullet) { get; } | Restituisce il formato dell'elenco puntato del paragrafo. Sola lettura [`IBulletFormat`](../ibulletformat). |
| [DefaultPortionFormat](../../aspose.slides/iparagraphformat/defaultportionformat) { get; } | Restituisce il formato della porzione predefinita di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [`IPortionFormat`](../iportionformat). |
| [DefaultTabSize](../../aspose.slides/iparagraphformat/defaulttabsize) { get; set; } | Restituisce o imposta la dimensione predefinita della tabulazione senza ereditarietà. Lettura/scrittura Single. |
| [Depth](../../aspose.slides/iparagraphformat/depth) { get; set; } | Restituisce o imposta la profondità del paragrafo. Il valore 0 indica valore non definito. Lettura/scrittura Int16. |
| [EastAsianLineBreak](../../aspose.slides/iparagraphformat/eastasianlinebreak) { get; set; } | Determina se l'interruzione di riga orientale asiatica è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [FontAlignment](../../aspose.slides/iparagraphformat/fontalignment) { get; set; } | Restituisce o imposta l'allineamento del carattere in un paragrafo senza ereditarietà. Lettura/scrittura [`FontAlignment`](../fontalignment). |
| [HangingPunctuation](../../aspose.slides/iparagraphformat/hangingpunctuation) { get; set; } | Determina se la punteggiatura sospesa è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [Indent](../../aspose.slides/iparagraphformat/indent) { get; set; } | Restituisce o imposta l'Indentazione della prima riga/Indentazione sospesa del paragrafo senza ereditarietà. L'Indentazione sospesa può essere definita con valori negativi. Lettura/scrittura Single. |
| [LatinLineBreak](../../aspose.slides/iparagraphformat/latinlinebreak) { get; set; } | Determina se l'interruzione di riga latina è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [MarginLeft](../../aspose.slides/iparagraphformat/marginleft) { get; set; } | Restituisce o imposta il margine sinistro in un paragrafo senza ereditarietà. Lettura/scrittura Single. |
| [MarginRight](../../aspose.slides/iparagraphformat/marginright) { get; set; } | Restituisce o imposta il margine destro in un paragrafo senza ereditarietà. Lettura/scrittura Single. |
| [RightToLeft](../../aspose.slides/iparagraphformat/righttoleft) { get; set; } | Determina se la scrittura da destra a sinistra è usata in un paragrafo. Nessuna ereditarietà applicata. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [SpaceAfter](../../aspose.slides/iparagraphformat/spaceafter) { get; set; } | Restituisce o imposta la quantità di spazio dopo l'ultima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura Single. |
| [SpaceBefore](../../aspose.slides/iparagraphformat/spacebefore) { get; set; } | Restituisce o imposta la quantità di spazio prima della prima riga in un paragrafo senza ereditarietà. Un valore positivo specifica la percentuale della dimensione del carattere che lo spazio bianco deve occupare. Un valore negativo specifica la dimensione dello spazio bianco in punti. Lettura/scrittura Single. |
| [SpaceWithin](../../aspose.slides/iparagraphformat/spacewithin) { get; set; } | Restituisce o imposta la quantità di spazio tra le linee di base in un paragrafo. Valore positivo indica percentuale, valore negativo indica dimensione in punti. Nessuna ereditarietà applicata. Lettura/scrittura Single. |
| [Tabs](../../aspose.slides/iparagraphformat/tabs) { get; } | Restituisce le tabulazioni di un paragrafo. Nessuna ereditarietà applicata. Sola lettura [`ITabCollection`](../itabcollection). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetEffective](../../aspose.slides/iparagraphformat/geteffective)() | Ottiene i dati di formattazione del paragrafo efficaci con l'ereditarietà applicata. |

### Osservazioni

Questa classe è usata per restituire e manipolare le proprietà di formattazione del paragrafo definite per il paragrafo specifico. Ciò significa che nessuna ereditarietà è applicata quando si ottengono i valori, quindi nella maggior parte dei casi si otterranno valori che indicano "non definito".

Per ottenere i valori effettivi dei parametri di formattazione includendo quelli ereditati è necessario utilizzare il metodo [`GetEffective`](./geteffective) che restituisce un'istanza [`IParagraphFormatEffectiveData`](../iparagraphformateffectivedata).

### Vedi anche

* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->